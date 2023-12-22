# Stochastic_Simulation

This repository is for the course Stochastic Simulaiton given at the Universiteit van Amsterdam. 
Created by Lisa Pahladsingh (13646566), Sanjhana Bhusal (14724383), and Victor Piaskowski (15132625)

The first assignment is located in the folder 'Assignment 1'. To run the script, open 
'Assignment 1/LisaPahladsingh_13846566_SanjhanaBhusal_14724383_VictorPiaskowski_15132625_Assignment1.ipynb' and run the notebook cells from start to finish. 
To run this, you need at minimum Python version 3.9 or higher and the following packages: statistics, PIL, numpy, pandas, matplotlib, colorsys, numba, and scipy.


The second assignment is located in the folder 'Assignment 2'. To run the script, open 
'Assignment 2/LisaPahladsingh_13846566_SanjhanaBhusal_14724383_VictorPiaskowski_15132625_Assignment2.ipynb' and run the notebook cells from start to finish. 
To run this, you need at minimum Python version 3.9 or higher and the following packages: To run this, you need at minimum Python version 3.9 or higher and the following packages: simpy, random, statistics, scipy, numpy, and matplotlib. 

The third assignment is located in the folder 'Assignment 3'. To run the script, open 
'Assignment 2/LisaPahladsingh_13846566_SanjhanaBhusal_14724383_VictorPiaskowski_15132625_Assignment3.ipynb' and run the notebook cells from start to finish. 
To run this, you need at minimum Python version 3.9 or higher and the following packages: To run this, you need at minimum Python version 3.9 or higher and the following packages: tsplib95, random, matplotlib, math, copy, and pandas


import tsplib95
import random
import matplotlib.pyplot as plt
import math
import copy
import pandas as pd

## Abstract For Assignment 1
The Mandelbrot set is a set that demonstrates incredible complexity from a simple equation. The Mandelbrot equation itself is f(z) = z^2 + c. The Mandelbrot set describes the set of complex values that do not diverge towards infinity. The goal of this paper is to calculate the area of the Mandelbrot set using a random, Latin hypercube, and orthogonal sampling method and comparing the results. The number of samples and the number of iterations are varied across runs, with the ultimate goal of comparing the estimated area and confidence interval across the different sampling methods. As a bonus, to attempt to reduce the variance, an antithetic variable is used. 