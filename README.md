# Gamma-Rediation
Overview
This is the code for Genetic Algorithms by @Sirajology on Youtube. In this demo code we use the MAGIC Gamma Telescope dataset to build a classifer. The classifier will train on the dataset and then be able to classify whether or not some energy is either Gamma Radiation or Hadron Radiation. Instead of guessing and checking the best ML model and hyperparameters to use, we use a genetic programming library called tpot to do that for us by trying out a bunch of them. See this link for an IPython notebook version of this code.

Dependencies
Numpy
tpot
scikit-learn
pandas
Use pip to install any missing dependencies

Usage
To run the demo code, after installing the dependencies, just run the following in terminal

python3 demo.py

Challenge
The challenge for this video is to use the TPOT library to make a discovery based on a question you pose. '

Step 1 - Download this Climate Change Dataset

Step 2 - Think of a question that this dataset will help you answer like "Has the temperature in India risen over the past 20 years?"

Step 3 - Clean the data and use TPOT to help you build a machine learning pipeline to answer your question

Step 4 - Post your GitHub link in the comments!

Credits
Credit for the vast majority of code here goes to Randy Olson. I've merely created a wrapper around all of the important functions to get people started.
