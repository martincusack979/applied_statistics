# Applied Statistics

This repository is submitted in partial fullfillment of a H.Dip in Science in Data Analytics. It contains all work undertaken in completing the module in Applied Statistics.

**Name: Martin Cusack**

**Student ID: G00239124**
***

## Contents 
* Introduction
* Tasks
* Project

## Introduction

This repository contains a Jupyter notebook named **tasks.ipynb**, a Jupyter notebook named **project.ipynb**, a text file named **requirements.txt**, a **.gitignore** file and a **readme** file.

**How to use this repository**

* Install the latest version of Visual Studio Code.
* Clone the repository at https://github.com/martincusack979/applied_statistics
* Open the repository in Visual Studio Code.
* Base environment (Python 3.9.18)
* Install the dependencies: pip install -r requirements.txt


# Tasks

  All work undertaken for the tasks in the Applied Statistics module is contained in a Jupyter notebook in this repository named **tasks.ipynb**

## Task 1 - Permutations and Combinations

### Task Description ### 

Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

Would you accept two errors? Explain.

## Task 2: numpy's Normal Distribution

### Task Description ### 

In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

## Task 3: t-Test Calculation

### Task Description ### 

Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.

Calculate the t-statistic based on this data set, using Python. Compare it to the value given by scipy.stats. Explain your work and list any sources used.

## Task 4: ANOVA

### Task Description ### 

In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0.

Now use a loop to perform the following test 10,000 times.

Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1.

Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type II error occurs.

Summarize and explain your results.

# Project

  All work undertaken for the project in the Applied Statistics module is contained in a Jupyter notebook in this repository named **project.ipynb**

  ### Project Description ###
  In this project, you will analyze the PlantGrowth R dataset. You will find a short description of it on Vicent Arel-Bundock's Rdatasets page. The dataset contains two main variables, a treatment group and the weight of plants within those groups.

  Your task is to perform t-tests and ANOVA on this dataset while describing the dataset and explaining your work. In doing this you should:

  Download and save the dataset to your repository.  Describe the data set in your notebook.  Describe what a t-test is, how it works, and what the assumptions are.  Perform a t-test to determine whether there is a significant difference between the two treatment groups trt1 and trt2.  Perform ANOVA to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2.

  Explain why it is more appropriate to apply ANOVA rather than several t-tests when analyzing more than two groups.

## References

(for tasks.ipynb)

[1]  *Python math.comb() Method.*  W3 schools. **www.w3schools.com/python/ref_math_comb.asp**

[2]  *numpy.unique.*  Numpy developers. **numpy.org/doc/stable/reference/generated/numpy.unique.html#numpy-unique**

[3] *numpy.random.normal.*  Numpy developers. **numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html#numpy-random-normal**

[4] *scipy.stats.shapiro.*  Geeks for Geeks.  **geeksforgeeks.org/how-to-perform-a-shapiro-wilk-test-in-python**

[5] *numpy.linspace.*  Numpy developers. **numpy.org/doc/stable/reference/generated/numpy.linspace.html**

[6] *Probability Density Function.*  **en.wikipedia.org/wiki/Probability_density_function**

[7]  *scipy.stats.ttest_ind.*  Scipy community. **docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html**

[8] *P-value*  **en.wikipedia.org/wiki/P-value**

[9] *Independent t-test for two samples.*  Laerd statistics. **statistics.laerd.com/statistical-guides/independent-t-test-statistical-guide.php**

[10] *Analysis of Variance (ANOVA).* Datatab team.  **datatab.net/tutorial/anova**

[11] *Type 1 and Type 2 errors.*  **en.wikipedia.org/wiki/Type_I_and_type_II_errors**

[12] *Sensitivity vs Specificity and Predictive Value* **statisticshowto.com/probability-and-statistics/statistics-definitions/sensitivity-vs-specificity-statistics/#SEN**

(for project.ipynb)

[1] *Results from an Experiment on Plant Growth.*  Vincent Arel Bundock. **vincentarelbundock.github.io/Rdatasets/doc/datasets/PlantGrowth.html**
[2] *seaborn.boxplot.*  Michael Waskom. **seaborn.pydata.org/generated/seaborn.boxplot.html**

[3] 

[4] 

[5] 

[6] 

[7] 

[8] 

[9] 

[10] 


