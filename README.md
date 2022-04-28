# FluidSim
This was a fairly simple project to complete as I wasn't required to actually build the simulation from scratch, merely add a few key functions.

1.- Create multiple sources for velocity and density
All that was needed here was to allow the program to read input files, and use them to insert these sources when declaring the simulation parameters, for which I simply used a JSON file

2.- Animate the velocity forces.
Just modify the coordinate/vector values during runtime by parsing them with the current frame the sim is on

3.- Create color schemas for the simulation.
They are actually already built into pyplot so all I needed to do was add in a keyword for them, these are listed here: https://matplotlib.org/stable/tutorials/colors/colormaps.html

4.- Simulate the presence of objects in the simulation.
I read the document you provided explaining how the simulation worked, and reasoned that an object would need to be an area where density and velocity are always 0, since there is no fluid where a solid exists
