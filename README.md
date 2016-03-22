MSR
===
Microstate sparse reconstruction, an optimization algorithm that solves the inverse problem: recovering an all-atom state consistent with a coarse-grained description.

AUTHOR
======
Andrew Abi-Mansour

INSTITUTION
===========
Department of Chemistry, Indiana University, Bloomington

PREREQUISITES
=============
ProtoMD - https://github.com/CTCNano/proto_md

PETSc - https://www.mcs.anl.gov/petsc

MDAnalysis - https://code.google.com/p/mdanalysis

Numpy - http://www.numpy.org

OpenMPI - http://www.open-mpi.org or MPICH  - https://www.mpich.org

WORKING EXAMPLE
===============
python MSRWriter.py struct traj tpr tol

-struct: structure file such as a pdb or gro file
-traj: trajectory file such as a trr, xtc, or dcd
-tpr: binary input file generated by Gromacs (with grompp) for reading topology
-tol: tolerance set for the atomic displacement, below convergence is assumed to be achieved
