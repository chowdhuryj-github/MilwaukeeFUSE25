

Data Cleaning Approach
 - for any datasets, fill in missing values using mean / median / mode or KNN
 - the type of tail for the feature, then using the type, determine method of filling in missing values
 - look at the units, and ensure thet units are standardized according to US (currency is $, length can be ft and in)
 - just for extra check, look for unique values within features
 - for any boolean features --> true is 1 and false is 0
 - for any categorical features --> if less than 4 to 5 unique values, encode them


dataset assignment 
- salvin: loan-test and loan-train
- mohana: student spending
- vaasu: loan-approval
- pa: credit-risk and udemy
