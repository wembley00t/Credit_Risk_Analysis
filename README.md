# Credit_Risk_Analysis

## Overview

Using the credit card dataset from LendingClub, a peer-to-peer lending services company, the following will be completed to predit credit risk:

  * Oversample the data using Random Over Sampler and SMOTE algorithims
  * Undersample the data using the Cluster Centroids algorithm
  * Combinational approach of over- and undersampling using the SMOTEENN algorithm
  * Compare two new machine learning models that reduce bias, Balanced Random Forest Classifier and Easy Ensemble Classifier

## Results

The below will desribe the balanced accuracy scores and the precision and recall scores of the six machine learning models.

#### Naive Random Oversampling

![Random Oversampling](https://user-images.githubusercontent.com/100876517/179440184-61cd8e66-d934-4037-b91f-c6977b9b23a2.png)

The balanced accuracy score is 64%.
The high risk population precision is .01 with 69%  sensitivity and a F1 of .02.
The low risk population precision is 1 with 59% sensitivity and a F1 of .74.

#### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/100876517/179440203-6eae0019-e299-4b5b-b9bf-83a049adf9ca.png)

The balanced accuracy score is 54%.
The high risk population precision is .01 with 63%  sensitivity and a F1 of .02.
The low risk population precision is 1 with 69% sensitivity and a F1 of .82.

#### Undersampling with Cluster Centroids Algorithm

![UnderSampling](https://user-images.githubusercontent.com/100876517/179440208-e6c595ff-2522-4ed9-9cc8-6896e34ae191.png)

The balanced accuracy score is 54%.
The high risk population precision is .01 with 69%  sensitivity and a F1 of .01.
The low risk population precision is 1 with 40% sensitivity and a F1 of .57.

#### Combination Over and Under Sampling with SMOTEENN

![Combo Sampling](https://user-images.githubusercontent.com/100876517/179440222-5867f5b9-9495-4a40-b92c-9ef13e6a26d1.png)

The balanced accuracy score is 64%.
The high risk population precision is .01 with 76%  sensitivity and a F1 of .02.
The low risk population precision is 1 with 59% sensitivity and a F1 of .74.


#### Balanced Random Forest Classifer

![Random Forest](https://user-images.githubusercontent.com/100876517/179440229-8fe140cd-3aa5-46b9-b50f-a0c150d838ea.png)

The balanced accuracy score is 79%.
The high risk population precision is .03 with 70%  sensitivity and a F1 of .06.
The low risk population precision is 1 with 87% sensitivity and a F1 of .93.


#### Easy Ensemble Classifier

![Easy Ensemble](https://user-images.githubusercontent.com/100876517/179440240-30a813f7-140d-4248-b4aa-1a82d9b5b0d4.png)

The balanced accuracy score is 93%.
The high risk population precision is .09 with 92%  sensitivity and a F1 of .16.
The low risk population precision is 1 with 94% sensitivity and a F1 of .97.






