# Assignment 5: Machine Learning in Python

This repository contains my work for assignment 5- machine learning in Python. This follows a tutorial online to build a machine learning program, and the goal here is to learn these skills to be able to apply them later in my research.

## Source

Tutorial followed:
https://machinelearningmastery.com/machine-learning-in-python-step-by-step/

## Contents

Assignment-5-Python
-.gitignore # Ignore notebook checkpoints
-README.md # This file
-environment.yml # Conda environment for this assignment
-python_5.ipynb # Notebook with completed exercises and comments

## Setting up the environment

I installed all the appropriate packages to create my environment and then cloned my github repo and added the environment.yml file. I also used .gitignore for the python notebook checkpoints folder.

## Following the tutorial

### Downloading, Installing, and Starting Python SciPy

I downloaded and added all of these required packages while setting up my environment, so this was already done. I just imported them in my jupyterlab terminal and notebook as well. The first command checks the version and makes sure it is all up to date.

### Load The Data

I had actually downloaded the data as a zip file for some reason, but I also followed the tutorial and downloaded it on the command line from a URL. I imported the associated libraries that we would be needing as well.

### Summarize the Dataset

In this section, we looked at the dimensions of the dataset, peeked at the data itslef, had a statistical summary of all attricbutes, and a breakdown of the data by the class variable. This was pretty straightforward.

### Data Visualization

In this section, we looked at two different plots. One was univariate, the other was multivariate. This is similar to what we did during Assignment 4, so again, pretty easy and straightforward.

### Evaluate Some Algorithms

Here's where we delve into the new stuff with choosing an algorithm to set up our machine learning!
We needed to separate out a validation dataset, set up the test harness to use 10-fold cross validation, build different models to predict species from flower measurements, and then select the best model. 

When spot checking and evaluating the algorithms, I received a large series of errors but the data still was produced. I think it just had something to do with a code being outdated. 

SVM ended up being the best model here with 97.7% predicted accuracy, so we moved forward using this one.

### Make Predictions

We then fit the model on the entire dataset and made predictions using SVM. Upon evaluating the predictions, we can see 96% accuracy, and the classification report showed great results. As the tutorial says, it is important to keep in mind that this is a small dataset.

## License

This repository is intended for educational use only.

## Acknowledgements

Based on exercises from https://machinelearningmastery.com/machine-learning-in-python-step-by-step/ 
Thanks to Dr. Jason Brownlee for sharing his expertise!