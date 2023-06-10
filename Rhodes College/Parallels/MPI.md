

```
mpicc -o foo foo.c

```


MPI has
- Local
	- Blocking: waits for op to complete
	- Non-blocking: starts op
- Synchronous: both parties have 
- Asynchronous: sender starts up without coordination for receiving


Guide: 

man MPI_init, man MPI_Finalize, MPI_Send
```c
int MPI_Init(int *argc, char ***argv)

int MPI_Comm_rank(MPI_Comm comm, int *rank)
```

```c
MPI_finalize
MPI_Comm_rank
MPI_Comm_size
MPI_send
MPI_Alltoall

```








```c
#Shows what is loaded by default

module list

# we want to see openmpi/gnu/4.1.5

```

```

# Read the mpitest.c included in the home directory



```

```c
if (rank ==0)
	MPI_Recv (1)
	MPI_Send (1)
else if (rank == 1)
	MPI_Recv (0)
	MPI_Send (0)
--> Deadlock


if (rank ==0)
	MPI_Recv (0)
	MPI_Send (0)
else if (rank == 1)
	MPI_Recv (1)
	MPI_Send (1)
--> Maybe deadlock depending on implementation



if (rank ==0)
	MPI_Send(1)
	MPI_Recieve (1)
else if (rank == 1)
	MPI_Recv (0)
	MPI_Send (0)
--> Guarantee no deadlock



```



![[Deadlock]]

```
MPI_Sendrecv (
)
```


```
MPI_Isend()


MPI_Test() -> To test things in MPI sender
```


| NULL        | First header | Second header |
| ------- | ------------ | ------------- |
| Value 0 | Value 1      |               |



