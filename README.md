# Prediction-Models

Data Science 
Data Available


Tables
train_set This table contains 8 numerical and categorical columns. The first column called Price is the target variable that we are the most interested in. X2 -> X7 are anonymized features. Finally, every row will have an unique ID and a Currency code.

test_set The test has identical schema to the train_set but the values of Price (and consequently Currency) are empty.

dimensions This table contains extra information relative to the unique IDs in train_set and test_set. Every ID can contain up to 3 extra variables that will be useful to add in the train_set and test_set to improve the predicitve power of any technique used.

exchange_rate Finally, exchange_rate contains the rate to use to convert between currencies and can be used to normalize the Price column in the train_set


Assignment Objective
Feel free to use any tools or technologies to complete the tasks below:
Data Cleaning
The candidate can freely clean/reshape the data as they like but some suggested steps are: • Convert all prices to GBP; • Include the metrics available in the ‘dimensions’ table into the train and test sets; • Impute missing values when opportune.

Exploratory Analysis
• Summary of the dataset and the characteristics you find interesting. • Please include a few visualizations to help you explain insights into the set.

Prediction
The test_set doesn’t contain the variable Price so we need you to try to predict the value of this variable. Please produce the following: • One model that is easy to understand and with a clear interpretation; • One model that is producing the best predictions accuracy. You are also asked to send us a file containing your best predictions for the variable Price of the test set before the interview. The submission file needs to contain the two following columns: • ID • predicted_price
