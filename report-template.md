# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The analysis was to prove how accurate our models were at predicting loans in general both healthy and high risk.

* Explain what financial information the data was on, and what you needed to predict.

The data was based on client variables that could alter their ability to pay backa loan.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

There was a significant diffrence in are number of high risk loands to helahty loand , we did over sampling to balance the value counts and make the analysis more accurate.

* Describe the stages of the machine learning process you went through as part of this analysis.

Preparing the data or Random oversampling.

1. Split features and labels
2. Creating train and test sets.
3. Initailizing and training the models
6. Random oversampling (2nd time)
4. Make predictions / tests
5. Generate performance metrics. (accuracy, confusion matrix, and callification report)

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

  Logistic regression was used becuase it was a binary test and has easy training and works well with binary classics.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

  Acuracy - Determines how accurate the model is with the data.
99.2%

                  Precision   Recall Scores
weighted avg       0.99       0.99       
                   99%        99%

* Machine Learning Model 2:

  * Description of Model 2 Accuracy, Precision, and Recall scores.
Accuracy
99.5%

                   Precision    Recall scores
weighted avg       1.0      1.0
                  100%      100%
                  99%         99%
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  The secind model perform best which has the over smampling included. This is due to testing samples sizes that are equivelant leads to more accurate respesentation of the data.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes, becuase it is more important to predict the ones becuase they are high risk and more likely to default / hurt the lender.
That is why the performance of the model that is being training by the over sampling data matters. to show how the change would be at higher levels of volume.
I do reccomend the logistic regression models from the data presented above.

If you do not recommend any of the models, please justify your reasoning.

