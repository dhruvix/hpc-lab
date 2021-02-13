# High Performance Computing Lab (CSL74)
### Question bank for semester 7, February 2021

no. | Question
------------ | -------------
1a. | Write an OpenMP program to perform addition of two arrays A & B store the result in the array C (Using Scheduling concept)
1b. | Write a CUDA program to print the message “Hello World” and demonstrate blocks by varying NUM_BLOCKS to different sizes.
2a. | Write an OpenMP program which performs C=A+B  & D=A-B in separate blocks/sections where A,B,C & D  are arrays.
2b. | Write a MPI program to send the message from a process whose rank=3 to all other remaining processes.
3a. | Write an OpenMP program to add all the elements of two arrays A & B each of size 1000 and store their sum in a variable using reduction clause.
3b. | Write a CUDA program to multiply two matrices.
4a. | Write an OpenMP program  to multiply two matrices A & B and find the resultant matrix C
4b. | Write a MPI program to send the message from a process whose rank=3 to all other remaining processes.
5a. | Write an OpenMP program to find the number of processes, number of threads, etc (the environment information).
5b. | Write a MPI program scatter the information to different processes (Consider at least Six Processes).
6a. | Write an OpenMP program to find the largest element in an array using critical section.
6b. | Write a CUDA program for adding two vectors.
7a. | Write an OpenMP program to show how thread private clause works.
7b. | Write a MPI program to find sum of 'n' integers on 'p' processors using  point-to-point communication libraries call
8a. | Write an OpenMP program to show how first private clause works.(Factorial program)
8b. | Write an MPI program where the master processor broadcasts a message “HELLO MSRIT” to the remaining processors using broadcast system call.
9a. | Write an OpenMP program  to multiply two matrices A & B and find the resultant matrix C
9b. | Write a CUDA program to print the message “Hello World” and demonstrate threads by varying BLOCK_WIDTH to different sizes.

To compile and run OpenMP programs:
```
gcc -fopenmp a.c
./a.out
```
To compile and run MPI programs:
```
mpicc a.c
mpirun -np 4 ./a.out
//4 = number of processes
```
To compile and run CUDA C programs:
```
nvcc a.cu
./a.out
```
Please star this repository if it helped you!
