Authors:
--------
Actual author of the thing: Giedrius Kudelis
             Just a helper: Ignas Anikevicius

Purpose:
--------
The simulation of gas particles in a container by using Leonard-Jones potential 
equations. This is just for fun and learning C++.

TODO:
----
    * Number crunching in C++
    * Implement Walls to the container by multiplying the velocity vector with a
        reflection matrix.
    * Create a way to plot a density plot instead of a simple "balls" 
        representing the particles.
    * Create a grid, which would divide the whole container into numerous regions
        which then would simplify the interactions between the particles a lot.
    * what about using the Monte Carlo method? if we take a random sample around
        the particle and assume, that all other particles are also randomly 
        distributed and the net force due to the calculated interactions is the 
        same, but larger for all interactions?

Graphical side:
--------------
    * Visualize everything using Matplotlib
    * Generate a movie from pngs.

Aditional things to try:
------------------------
    * Try to implement the heating mechanism, where the particles interacting with
        the walls of the container would gain kinetic energy, and thus, they would
        increase the temperature of the gas cloud.
    * Try to do some quantum computation for monoatomic gases (like Helium).
    * Try to implement everything in Cython (and SAGE) and see whether it is any 
        faster. NOTE: SAGE has it's own animation mechanism.
