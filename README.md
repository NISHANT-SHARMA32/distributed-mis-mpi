# Distributed Maximal Independent Set (MIS)

This project implements distributed MIS algorithms using MPI and C++.

Algorithms implemented:
- Baseline MIS
- Luby's Randomized MIS
- Ghaffari's MIS

Technologies:
C++, MPI, Distributed Graph Algorithms

Run example:
mpic++ luby_main.cpp -o luby
mpirun --oversubscribe -np 18 ./luby Input Output
