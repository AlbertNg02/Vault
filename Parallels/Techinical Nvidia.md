


128 SMs per full GPU A100
Warp = 64 * 32 
32 blocks / SM 
1024 threads / block
MMM = 1block

```


dim3 g(1,1)
dim3 b(32,32)
cukern<<<grid,block>>>()


# Each dimension is capped at 65k

since there is only 1024 threads -> squared -> cap at 32 by 32 matrixes

```

block are 2x2 threads
grid is 2x2 block
![[Techinical Nvidia 2023-04-21 11.27.45.excalidraw]]

Pd[1][2] computed by t10 in b0

```
__global__ void MMK()
int row = blockldx.x * tile-size + threadsldx.x;
int col = blocklde.y * tilesize + threadldx.y

double Pval = 0.0

for (int k = 0; k < width; k++)
	Pval += Md[row * width + k*] + Nd[k*width + Col]
Pd[row * width + col] = Pval;

```