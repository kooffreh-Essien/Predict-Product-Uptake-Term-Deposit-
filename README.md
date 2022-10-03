# Predict Product Uptake Term Deposit

# Introduction
The goal of this project is to build a machine learning model that is able to predict if customers will subscribe to term deposit.

# Data Sourcing
The dataset was gotten from Kaggle from a public publication. Reference to the dataset will be included in the repo.

# Data Transformation
- All the features ha thier data types stored as objects. So I had to convert the columns to their repective formats.
- There were no missing values.

# Findings and Recommendations
Four (4) algorithms were used in building this model and were evaluated using accuracy, precision and recall. Of all the algorithms used, Random Forest gave the best accuracy and thus considering the business problem, I had to consider precision as we want to be able to target the exact customers that would subscribe to term deposit.

## Recommendation
Going forward, I would have to carry out hyper parameter tuning, possibly scaling for some algorithm to enable me get a higher accuracy and precision.
