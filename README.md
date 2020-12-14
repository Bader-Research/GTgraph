# GTgraph: A suite of synthetic random graph generators

GTgraph was developed for the [9th DIMACS Shortest Paths
Challenge](http://www.dis.uniroma1.it/~challenge9/). The following
classes of graphs are currently supported:

Input graph instances used in

- the [DARPA HPCS](http://www.darpa.mil/Our_Work/MTO/Programs/High_Productivity_Computing_Systems_%28HPCS%29.aspx) SSCA#2 graph theory benchmark (version 1.0).
- Erdös-Rényi random graphs.
- Small-world graphs, based on the [Recursive Matrix (R-MAT) model](http://www.cs.cmu.edu/~christos/PUBLICATIONS/siam04.pdf).

The generators write graphs to disk in the plain text DIMACS Challenge
format described [here](http://www.dis.uniroma1.it/~challenge9/format.shtml). The file [sample.gr](sample.gr) contains a sample graph instance.

A brief overview of the generators is described in [gen.pdf](gen.pdf).

Please see the [README](README) for installation and usage of this package.

Please contact Kamesh Madduri or David A. Bader if you encounter any
problems building/running the code.
