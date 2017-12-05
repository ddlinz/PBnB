## PBnB version 0.1 ##\
# An implementation of the Probabilistic Branch and Bound
# version based on research published most recently in the paper
# "Partition-based Approach to Level Set Approximation for Simulation Optimization" by Huang and Zabinsky 2014
# published in the proceedings of the winter sim
##

## CONTENTS 
# main program files
c_SubRegion.py - the class of subregions that will track the points sampled
fun_PBnB_supplements - the suplemental functions that branch, sample, and prune the subregions tracked by PBnB
m_initial_parameters_setting.py - the object that controls the parameters for the PBnB run
PBnB.py - the main PBnB algorithm loop, along with a default test function 'main'

# test functions 
testfunction_rosenbrock - a test function of the 2D rosenbrock function
testfunction_shifted  - a test function of the 2D sinusoidal function

## DIRECTIONS
To run the basic program output, the PBnB.py file. The 'main' function will run a default version of the program and output three named files "Rosenbrock_test_DATE.png" that show the 2-dimensional picture of the approximated level-set on the tested domain. 
In order to modify the function that is run or the optimizer parameters, modify "fun_blackbox" variable to the name of the new function to be optimized and modify parameters located in the "m_initial_parameters_setting.py" file. 

## CITATION INSTRUCTIONS
Posted software is available for free for research purposes under conditions of fair attribution. Please cite the listed research when using code for future scientific and engineering applications.
