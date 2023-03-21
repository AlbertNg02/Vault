

```Setup
module list
module unload openmpi
module load ucx openshmem
make
```

```Run Command
srun -n 11 lab3 -n 11 -t 10
```


```remove
scancel id
```



Terms
- Super non linear performance ( impossible cuz parallel only adds overhead and communication)
- Eureka problems


```
Body 0 location: 1009.999999 - 1269.999999 - 1529.999998
Body final location: 1025907.500059 - 2026067.500118 - 3026227.500177
```