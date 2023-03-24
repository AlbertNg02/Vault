

```c
#prama omp parallel for
for i
	for j
		for k
			  #pragma omp critical
			  c[i][j] += a[i][k] * b[k][j]
```

a and b are only being read
c is a read and write
	If we parralelize on the outer most loop which is i they all have their distinct i ![[pragma]]

Locking inside innermost loop 



