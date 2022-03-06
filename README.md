# DSCI 100 project proposal
1. Title: Prediction of Heart Disease based on Cleveland's Dataset
2. Introduction:
Provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your proposal. Clearly state the question you will try to answer with your project. Identify and describe the dataset that will be used to answer the question.

Predictors: age, resting blood pressure, serum cholesterol, fasting blood sugar, max heart rate

3. Preliminary exploratory data analysis:
Demonstrate that the dataset can be read from the web into R. Clean and wrangle your data into a tidy format. Using only training data, summarize the data in at least one table (this is exploratory data analysis). An example of a useful table could be one that reports the number of observations in each class, the means of the predictor variables you plan to use in your analysis and how many rows have missing data. Using only training data, visualize the data with at least one plot relevant to the analysis you plan to do (this is exploratory data analysis). An example of a useful visualization could be one that compares the distributions of each of the predictor variables you plan to use in your analysis.
4. Methods:
Explain how you will conduct either your data analysis and which variables/columns you will use. Note - you do not need to use all variables/columns that exist in the raw data set. In fact, that's often not a good idea. For each variable think: is this a useful variable for prediction? Describe at least one way that you will visualize the results
--
In order to conduct the data analysis, the columns selected to be most relevant are age, sex, number of major vessels, old peak, fasting blood sugar and maximum heart rate. These variables will be the most useful in predicting heart disease amongst new patients at the Cleveland Clinic, as they were the most correlated amongst the previous patient diagnoses in the data set. For example, heart disease risk was shown to triple with each decade of life, which demonstrates the significance of age as a predictor. The results will be visually represented by a line graph, with the given predictive variable on the x-axis (eg. Maximum Heart Rate (BPM)) and the density of applicant individuals on the y-axis. 
5. Expected outcomes and significance:
What do you expect to find? What impact could such findings have? What future questions could this lead to?
