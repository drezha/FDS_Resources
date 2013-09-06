# FDS Resources

This repo contains a number of resources for the Fire Dynamics Simulator
package.

## FDS Benchmarking

FDS is a CPU intensive operation, with models sometimes taking many days to
complete. Having a faster CPU may not also provide the best speed for running
the models. This section looks at the different processors available and how
they compare against one another.

It looks at both single core and multi core processing. Please note the
disclaimer that this is solely a comparison and various other factors can affect
the speed.

You can view the results here:  
[Single Core](https://github.com/drezha/FDS_Resources/blob/master/FDS%20Benchmarking%20Files/Single%20Core%20Benchmarks.md)   
[Multi Core](https://github.com/drezha/FDS_Resources/blob/master/FDS%20Benchmarking%20Files/Multi%20Core%20Benchmarks.md) 

## FDS Properties

NIST stopped including material properties with the release of version 5. This
section aims to construct a database of properties (with references) for use in
FDS CFD models. The output is an FDS file, created by [Pyrosim](www.thunderheadeng.com/pyrosim/).
