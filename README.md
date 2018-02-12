# Decision Tree Implementation Assignment Code
My manual implementation of a Decision Tree for an assignment in the [Machine Learning: Classification](https://www.coursera.org/learn/ml-classification) course on Coursera.

The goal of the assignment was to **implement a decision tree by hand** in order to understand how they work, however the provided starter code was not vectorized and somewhat messy so I decided to perform [my own implementation from scratch](https://github.com/JP-DataScienceProjects/DecisionTreeImplementation/blob/master/Code/DecisionTreeImplementation.ipynb).

## Result
From the assignment instructions below, **training a decision tree** using the provided **starter code** would take approximately **one minute**, however the training time I was able to achieve on a dataset of approx. 40k rows was **1.5s on average** (second screenshot) - a **speedup of ~40x**:

**Training Instructions** (indicating ~60s training time with the non-vectorized starter code):
![alt text](https://github.com/JP-DataScienceProjects/DecisionTreeImplementation/blob/master/Screenshots/TrainingInstructions.png)

**Actual Training Time** (using with my vectorized, hand-coded decision tree implementation):
![alt text](https://github.com/JP-DataScienceProjects/DecisionTreeImplementation/blob/master/Screenshots/TrainingTime.png)
