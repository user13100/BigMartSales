# BigMartSales

Sales Prediction for Big Mart Outlets The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly.

Data Dictionary We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

Train file: CSV containing the item outlet information with sales value

### Problem Statement
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

### About Dataset
We have train and test data set. Train data set has both input and output variable. You need to predict the sales for test data set.

- Number of observations in Train set: 8523
- Number of observations in Test set: 5681

### Data Download
You can download the dataset from our Datahack Platform. Several Machine Learning and Deep Learning competitions are hosted on this platform. It gives you the following functionalities:

You can view and compare your score against that of other participants on the leaderboard. You can also keep track of your submissions.

### Approach to the Problem
- Pre-process the data: impute the missing values, normalize the variables. etc.
- Define the architecture of your model
- Since it is a regression problem, make sure that you use the 'linear' activation function in the output layer
- Train your model
- Do the same pre-processing steps on test set as you did for the training set
- Generate predictions for the test set using the trained model
- Save the predictions in a csv file (to check the format, refer to the sample submission file provided on the problem page)
- Submit your predictions on the problem page and check your rank on the leaderboard.
