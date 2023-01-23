# 108_days_of_ML
This repository consists of all my learnings in Machine Learning

Day 1: Data Preprocessing Steps 

Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model. It is the first and crucial step while creating a machine learning model.

I have considered a simple data set for doing data preprocessing,
Steps involved:
Step 1 - Importing the necessary libraries 

Step 2 - Importing the data

Step 3 - Handling of Missing Data:
         There are two prominent ways to handle a missing data:
         1.Deleting the particular row - This method is not optimal as this could lead to loss of Data. 
         2.Calculating the mean: Calculating the mean of that column or row which contains any missing value and will put it on the place of missing value.
         
Please Note that missing data treatment will always depend on the nature of the data and business. Therefore, it should be done only after consulting a Business Analyst or SME.         

Step 4 - Encoding Categorical data:
         Since machine learning model works on mathematics and numbers, but if the dataset would have a categorical variable, then it may create trouble while building          the model. So it is necessary to encode these categorical variables into numbers.
      
Step 5 - Splitting the Dataset into the Training set and Test set:
         Train set: The training dataset is a set of data that was utilized to fit the model. The dataset on which the model is trained. This data is seen and learned          by the model. 
         Test set: The test dataset is a subset of the training dataset that is utilized to give an accurate evaluation of a final model fit.
         
Step 6 - Feature Scaling:
         Feature scaling is the final step of data preprocessing in machine learning. 
         It is a technique to standardize the independent variables of the dataset in a specific range. 
         In feature scaling, we put the variables in the same range and in the same scale so that no any variable dominate the other variable.
         
