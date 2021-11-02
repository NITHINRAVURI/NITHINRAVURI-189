# NITHINRAVURI-20191IST0189-Simple Linear Regression[ (4 Model) R^2 - 97.3%)]
# Problem Statement
The head of HR of a certain organization wants to automate their salary hike estimation. The organization consulted an analytics service provider and asked them to build a basic prediction model by providing them with a dataset that contains the data about the number of years of experience and the salary hike given accordingly. Build a Simple Linear Regression model with salary as the target variable.

Definition of Variable -:

Year of Experience (Input) Salary Hike -> Hike in salary (Target)
#Approach to Solve the Business Case -:
1 Business Objective - Find Relationship between Salary Hike and Year of Experience
2 Perform EDA on data (Outlier, Missing Values).
3 Understand the relationship between the variable's using Scatter Plot.
4 Apply Simple linear regression with OLE to create base regression model( Vanilla Model)
5 Check the RMSE, R^2 & R values for the model.
6 Compare the Vanilla model with Model with Transformation's to check the best fit model.
Transformation used
A Logarithmic
B Exponential
C Polynomial with degree 2
7 After comparing RMSE, R^2 & R values, Select the best model.
8 Train & Test your data on these model to check the performance of model on test data.
#Exploratory Data Analysis
1 Check for the null Values in dataset.
2 Check for the outlier in dataset
# Final Observation

Although Train data is giving better result than test data hence it looks like an overfit model. But since the RMSE value of Train & Test data is very Close, it can be Inferred Model will perform well in real life scenario with Unknown Data. Hence, we can predict the Salary Hike with higher accuracy based on Year’s of Experience data.

#Final R^2 Value = 97.3%
