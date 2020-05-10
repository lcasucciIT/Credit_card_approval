# Credit_card_approval
Analysis of credit card approval with the uci dataset - source http://archive.ics.uci.edu/ml/datasets/Credit+Approval

All attribute names and values have been changed to meaningless symbols to protect confidentiality of the data.

This dataset is interesting because there is a good mix of attributes -- continuous, nominal with small numbers of values, 
and nominal with larger numbers of values. There are also a few missing values.

The source is http://archive.ics.uci.edu/ml/datasets/Credit+Approval
    
The values from A1 to A15 represent features that would lead to a + o - (positive or negative) credit card approval application.

Business Problem: Banking industries received so many applications for credit card request. Going through each request manually can be very time consuming, also prone to human errors. However, if we can use the historical data to build a model which can shortlist the candidates for approval that can be great.

Approach: By analyzing the data, we will build a predictor model by using some well-known pre-processing methods such as imputing missing values, label encoding, scaling the columns values and finally applying the model on training data set and evaluating the model with testing data set. We will also see a few additional approaches on how to improve the model performance.
