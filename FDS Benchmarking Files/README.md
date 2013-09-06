# FDS Benchmarking

Benchmarking FDS on different computer systems is an important step in seeing
how a computer setup is likely to compare to others in terms of running a model.

This following files allow this to be done. Distributed with FDS 5 (and for some
reason stopped in FDS 6), the following files allow you to run a comparison
between systems and compare how they perform.

There are two different FDS. Below is the process to running them both
individually to provide results for the benchmarking table here. 


*Note these are simplistic models, designed solely to get a comparison between
different CPU's and different operating systems. Note that many other factors
may affect the performance of a system and* **therefore this should only be used
as a guide** . I take no responsibility for purchasing decisions based on these
results - they are purely "an estimate" of the speed you're likely to see.

## Single Core Benchmark

To run the single core benchmarks, you need to download the [bench1.fds](https://raw.github.com/drezha/FDS_Resources/master/FDS%20Benchmarking%20Files/bench1.fds)
file and run that in FDS using the command:

    fds bench1.fds

When complete, open the bench1.out file and go to the bottom of the file. This
will then show you the elapsed time taken to run the model. This will test a
single core on your machine. 

## Multi Core Benchmark

Multi core benchmarking requires the installation of an MPI program. NIST
recommend [MPICH](http://www.mpich.org/) for Windows and Mac and [LAM](http://www.lam-mpi.org/)
on Linux.

Once you have the MPI program installed, you need to use the MPI enabled FDS and
set the program to run.

On linux, this can be achieved using the command:

    mpirun -np X fds5_mpi scale1.fds    

where X is the number of cores the machine has.

On Windows, this can be achieved with:

    mpiexec.exe -n X  -localonly -noprompt fds5_mpi_win64.exe scale1.fds

## Results

Once the models have run, the results are in the bench.out and scale1.out file,
dependant on the test you ran. The results are at the bottom of the file.
