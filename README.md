# AMBER-TC-INTERFACE
A file from AmberTools/SANDER program that manages communication with TeraChem

The initial version was taken from AmberTools19: 
`amber18/AmberTools/src/sander/`

Here we manage modifications for our own use, specifically:

1. Bugfix for MPI interface, which is now double counting Couloumb interactions.
2. Extension for Amber-driven REMD with multiple TC servers
