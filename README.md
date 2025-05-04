# Classification

Prereqisites:
-------------
This module assumes that you are familiar with the following concepts

    a. Introduction to Machine Learning
    b. Linear Regression
    c. Logistic Regression

--------------------------------------------------------------------------

In Logistic Regression, we used the Sigmoid function to convert raw model output to a value between 0 and 1 to make probabilistic predictions. But what if your goal is not to output 
probability but a category. For example, Whether on particular day, it may rain or not 

Classification:
-----------------
  a. Classification is a taks of predicting which sets of classes (categories) an example or an object belongs to.
  b. Here we will learn how to convert a logistic regression module that predicts a probality into a binary classification model that predicts one of the two classes.
  c. Also here we will learn how to choose and calculate appropriate metrics to evaluate the quality of classification model's prediction.

--------------------------------------------------------------------------

Thresholds and the confusion matrix:
--------------------------------------

  a. Let us say you have a logistic regression model that predicts a value between 0 and 1. Now in order to classify the example or object into categories, you need to convert 
      the probability value into one of the two categories.
  b.  To convert the model's raw numerical output into categorical values we use a threshold probability called a Classification threshold. 
  c. Then examples or objects with a probability above the threshold value are assigned to the positive class.
  d. Examples or objects with w probability value less the threshold value are assigned to the negative class.

Confusion Matrix:
------------------
a. The probility score is not reality or Ground Truth.
b. For each output from a binary classfier there are four possible outcomes.
c. A confussion matrix is formed by laying out Ground Truths as columns and the models's prediction as rows.
https://developers.google.com/machine-learning/crash-course/classification/thresholding?authuser=1

  
  



