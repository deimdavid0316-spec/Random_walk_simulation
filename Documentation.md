# Random Walk Simulation Project
## Documentation
### Deim Dávid (CW2DKK) & Henrieta Horváth (CWKQJB)
## Task 1 - Simulating the motion
It simulates the nearest-neighbour random walks, for multiple walkers in 2D and 3D. It stores and tracks the full trajectory for later analysis. 
The lattice motion function 
* At each step moves one unit in a uniformly random possible direction in the corresponding dimension.
* It draws the random direction indices with seeded random number generator. 
* Converts indices into displacement vectors, it sums them so it gets the position.
* Returns an array of every walker’s position at every step and prefixed with the origin.
