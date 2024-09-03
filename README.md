# EXPERIMENT 2 - Numerical Python
This repository contains my solutions for the second experiment in ECE 2112: Advanced Computer Programming and Algorithms. I've used Jupyter Notebook to implement and test my Python code. The code will automatically print the results.

## Problem 1: NORMALIZATION
Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and .std() calls. In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy.

## Problem 2: DIVISIBLE BY 3
Create the following 10 x 10 ndarray. Which are the squares of the first 100 positive integers. From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

## Sample Output
Problem 1
```
[[ 0.47432996  1.10396036 -0.87130122 -0.06634469 -0.71923798]
 [-1.12162842 -0.17793388  0.54674556  0.02008209  0.57701171]
 [-1.42005653 -0.73683554 -1.3709721  -1.36999142  1.5232591 ]
 [-0.78413423  0.3528315   1.68472177 -0.91009895 -0.36230985]
 [-0.85643599  0.83177374  2.07643694  1.10506191  0.47106615]]
```

Problem 2
```
[   9   36   81  144  225  324  441  576  729  900 1089 1296 1521 1764
 2025 2304 2601 2916 3249 3600 3969 4356 4761 5184 5625 6084 6561 7056
 7569 8100 8649 9216 9801]
```
