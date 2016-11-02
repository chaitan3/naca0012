Install OpenFOAM and octave

Modify meshgen.m to change angle of attack, Reynolds number (directly proportional to scale multiplied by chord).

To change Mach number, change p0 (stagnation pressure), using the isentropic relation for the boundaries "inlet" and "topAndBottom" in 0/p 

To generate the mesh run create_mesh.sh in the repository folder.

Run the solver using "rhoCentralFoam?"
