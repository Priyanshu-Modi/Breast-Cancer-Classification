# Breast-Cancer-Classification
Breast Cancer Classification using Machine Learning 

## Abstract

Breast cancer is one of the leading causes of death by cancer for women. The automatic detection of breast cancer cells by analyzing histopathological images plays a significant role for patients and their prognosis.In this project,we aim  to build a better understanding of how to choose model when we deal with cancer detecting task.

## Metrics

In tumor cells classification is important to avoid false negatives because if a malignant tumor is predict as benign the patient will not receive treatment. That's why F1 is a ideal metric to score our model.

@ recall = True positive / (True positive + False negative)

@ precision = True positive / (True positive + False positive)

The final model I will analyze the model performance ploting a confusion matrix and score model using F1 Score that is a methot to measure performance of binary classification, the F1 score is a measure of a test's accuracy, is the harmonic average of the precision and recall, where an F1 score reaches its best value at 1 (perfect precision and recall) and worst at 0.
 
In statistical analysis of binary classification, the F1 score is a measure of a test's accuracy. It considers both the precision p and the recall r of the test to compute the score: p is the number of correct positive results divided by the number of all positive results returned by the classifier, and r is the number of correct positive results divided by the number of all relevant samples (all samples that should have been identified as positive). The F1 score is the harmonic average of the precision and recall, where an F1 score reaches its best value at 1 (perfect precision and recall) and worst at 0.

## Machine Learning Algorithm

@ Logistic Regression

Was developed by statistician David Cox in 1958. The binary logistic model is used to estimate the probability of a binary response based on one or more predictor (or independent) variables (features). It allows one to say that the presence of a risk factor increases the odds of a given outcome by a specific factor. The model itself simply models probability of output in terms of input, and does not perform statistical classification, though it can be used to make a classifier, for instance by choosing a cutoff value and classifying inputs with probability greater than the cutoff as one class, below the cutoff as the other.

## RESULTS

In order to solve our objective or we can say try to predict the problem of Breast Cancer we succesfully train and test a model using appropte dataset.
By Preprocessing we remove some of the unnecessary features or add some of the requirements.
After splitting dataset into two parts -- Training and Testing Datasets.
we use Lofgistic Regression algorithm to train the model. 
we get a good accuracy of  : 
     @ Accuracy on training data =  0.9494505494505494
     @ Accuracy on test data =  0.9298245614035088
     
After this we also test our model by a random input set and a satisfacoty result.
