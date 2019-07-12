# AML_2019_Group8

## Part 1 

### Why is gradient descent important in machine learning? 

Gradient descent is an optimisation algorithm used to minimise functions by iteratively moving in direction of steepest descent defined. In machine learning, we use gradient descent to update parameters of model, which refers to coefficients in linear regression. 
It is one of the basic and simple tools to optimise arbitrary objective functions. Using gradient descent can lead to a better control of algorithm as the process of learning parameter, it allows users to control step size. 

### How does plain vanilla gradient descent work? 

A vanilla gradient descent, also known as batch gradient descent, is a usual, standard or unmodified of values. Gradient is computed as the average of gradient of each datapoint. It calculated the error for each observation in the dataset and perform updates after all observation have been evaluated. The flaw of vanilla gradient descent is as it represents a huge consumption of computational resource, entire dataset needs to remain in memory. 

### Two modifications to plain vanilla gradient descent.

We use two modifications below to show our result, multi-variable and basic. Multi-variable is to find the best route through ‘scanning’ 360 degree around single datapoint to find the steepest point. Features can be added for this gradient descent as each feature is represented as a dimension.
The basic gradient descent is a limited version of multivariable gradient descent. In every step, only 4 directions will be considered, and it starts randomly in any direction. Therefore, if the dataset is so huge or tend to infinity, if the point begins with wrong direction, it will be really hard to find the minimum value. 

## Part 2 - Refers to ``

## Part 3 - Investigate the ability of vanilla gradient descent to find the global minimum

## Part 4 - Compare the performance of two variants of gradient descent 






