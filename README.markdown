Authors:
--------
Actual author of the thing: Giedrius Kudelis
             Just a helper: Ignas Anikevicius

Purpose:
--------
The simulation of gas particles in a container
  by using Leonard-Jones potential equations.

TODO:
----
    * Number crunching in C++
    * Implement Walls to the container by multiplying the velocity vector with a
        reflection matrix.
    * Create a way to plot a density plot instead of a simple "balls" 
        representing the particles.
    * what about using the Monte Carlo method? if we take a random sample around
        the particle and assume, that all other particles are also randomly 
        distributed and the net force due to the calculated interactions is the 
        same, but larger for all interactions?
    * Try to do some quantum computation for monoatomic gases (like Helium).
    * Visualize everything using Matplotlib
    * Try to implement everything in Cython (and Sage) and see whether it is any 
        faster.
