# Clickbait Detection Using Bayesian Classifier

## Overview

This project aims to detect clickbait using a Multinomial Naive Bayes classifier. The process involves data preparation, creating the classifier, hyperparameter tuning, model selection, and identifying key indicators of clickbait.

## Data Preparation

### Reading and Preprocessing Data:
- Read clickbait and not-clickbait datasets.
- Merge and shuffle the data.
- Split the data into training, validation, and testing sets.

### Target Rate Calculation:
- Compute and print the target rates of the datasets.

## Multinomial Naive Bayes Classifier

### Creating the Classifier:
- Develop a pipeline for training the Naive Bayes classifier.
- Fit the training data using the classifier model.

### Evaluate Performance on Training and Validation Data:
- Obtain predictions and compute precision, recall, and F1-Score for training and validation datasets.

## Hyperparameter Tuning

### Hyperparameter Tuning:
- Tune at least 3 hyperparameters to enhance the model's performance.
- Perform a grid search using the ParameterGrid class.
- Identify the best metrics.

## Model Selection

### Selecting the Best Model:
- Utilize the best model parameters obtained from hyperparameter tuning.
- Fit the training data using the best parameters.
- Make predictions on the test data.

### Evaluate Performance on Testing Data:
- Compute precision, recall, and F1-Score for testing data.

## Key Indicators

### Identifying Key Indicators of Clickbait:
- Determine words identified as key indicators of clickbait.
- Use log probabilities to find the top 5 key indicators.

## Conclusion

The project successfully implements a clickbait detection system, achieving notable performance on both training and testing datasets. Refer to the steps above for a detailed understanding of the project's workflow.

## References:
1. [Insights on precision, recall, and F1 score.](https://towardsdatascience.com/a-look-at-precision-recall-and-f1-score-36b5fd0dd3ec)
2. [Clickbait Dataset](https://github.com/pfrcks/clickbait-detection/blob/master/clickbait)
3. [Not Clickbait Dataset](https://github.com/pfrcks/clickbait-detection/blob/master/not-clickbait)
4. Agrawal, A. (2016). "Clickbait detection using deep learning." In 2nd International Conference on Next Generation Computing Technologies (NGCT) (pp. 268–272).

