# Global Self-consistent, Hierarchical, High-resolution Geography Database in High Rez for R

The high resolution data from:  https://www.soest.hawaii.edu/pwessel/gshhg/  imported into R.

The R 'world.f.borders.lakes.rivers.RData' file contains 5 R matrix objects

world.f.borders, 
world.f.island, 
world.f.lake,
world.f.pond.in.island, and 
world.f.rivers

The R object 'world.f.land' has been spit into 2 files; 'world.f.land.A.RData' and 'world.f.land.B.RData'.

The R function 'Git.World.f.HiRez' included in this repository and the Imap package (https://github.com/John-R-Wallace/Imap) will download the 'world.f' RData files, import them into R, and recombine the 'world.f.land' R object.

A low resolution of version of these files is included with the Imap package.
