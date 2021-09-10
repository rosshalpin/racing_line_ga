# racing_line_ga

Genetic Algorithm to obtain a racing line on a given inputted track. A racing line being the optimal path around a race course with some given vehicle parameters.

Completed in part towards achieving a Level 8 Higher Diploma in Artificial Intelligence Applications.


Takes a set of input points and interpolates a center line spline from those inputs. 
A track is then drawn around this center line defining the limits of the track.
Sample squares are then created around the track and visualised. 
Within each sample square a random point is chosen.
With all of these random points a new spline defining a random sub-optimal racing line is interpolated.

Implementing Genetic Algorithm operations of selection, crossover and mutation, we attempt to find a more optimal solution to generating a racing line. 
A fitness function which uses a generalised vehicle simulation, determines the length of time to traverse a given track. 

Random generated racing lines with 50 generations and population of 500:

Best time:  311.2580106466346
Average Best Time:  314.28778991582976
Average Worst Time:  326.6378874060011
Average Time:  321.0960511052866

Racing line optimisation with 50 generations and population of 500
Best time:  309.00084374047975
Average Best Time  309.97085054308224
Average Worst Time  321.9977028304318
Average Time  314.9527337410784
