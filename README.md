
## Project Overview

In this section, we'll look at a credit card fraud detection dataset, and build a binary classification model that can identify transactions as either fraudulent or valid, based on provided, historical data. In a 2016 study, it was estimated that credit card fraud was responsible for over 20 billion dollars in loss, worldwide. Accurately detecting cases of fraud is an ongoing area of research.  

The payment fraud data set (Dal Pozzolo et al. 2015) was downloaded from Kaggle. This has features and labels for thousands of credit card transactions, each of which is labeled as fraudulent or valid. In this notebook, we'd like to train a model based on the features of these transactions so that we can predict risky or fraudulent transactions in the future.
Binary Classification
Since we have true labels to aim for, we'll take a supervised learning approach and train a binary classifier to sort data into one of our two transaction classes: fraudulent or valid. We'll train a model on training data and see how well it generalizes on some test data.

The notebook will be broken down into a few steps:

Loading and exploring the data
Splitting the data into train/test sets
Defining and training a LinearLearner, binary classifier
Defining and training a LinearLearner, binary classifier
Making improvements on the model
Evaluating and comparing model test performance
Making Improvements
A lot of this notebook will focus on making improvements, as discussed in this SageMaker blog post. Specifically, we'll address techniques for:

Tuning a model's hyperparameters and aiming for a specific metric, such as high recall or precision.
Managing class imbalance, which is when we have many more training examples in one class than another (in this case, many more valid transactions than fraudulent).
## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
		git clone https://github.com/kondra50/fraud_detection.git
		cd fraud_detection
	

### Notes
In this project , we see how to use Amazon Sagemake built-in linear model for binary classification.
We review how to improve model by tuning precision/recall values and also see how to deal with imbalance label distribution.
