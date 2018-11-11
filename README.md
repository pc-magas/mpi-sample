A sample code to test whether mpi works to your machine.

Over GNU linux compile with:

```
mpicc -o ^output_file^ mpi.c
```

And run it with:

```
mpirun -np ^cluster_size^ ^output_file^
```
