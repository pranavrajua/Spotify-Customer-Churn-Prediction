# Spotify-Customer-Churn-Prediction
The purpose of this project is to analyze web log data of music streaming services to predict customer churn using Pyspark and SparkML algorithms.

In this streaming
service, users can either listen to music for free or buy a subscription. Customer churn
prevention is a hot and challenging problem in almost every product and service
company. Predicting customer churn is a challenging and common problem that data
scientists encounter these days. The ability to predict that a particular customer is at a
high risk of churning, while there is still time to do something about it, represents a huge
additional potential revenue source for every customer-facing business.If companies
were able to utilize customer-usage data to find unique trends and accurately map them
to indicate which customers may churn, it would be possible to incentivize customers to
remain using their services giving them a loyal customer base which is key for a
company’s growth.
In order to identify users who are likely to churn, it’s important to perform an exploratory
analysis to glean insights from the data set and identify key variables of interest. The
next process is to experiment with different model algorithms and then select the best
model based on key evaluation metrics such as F1 Score and accuracy using Spark ML
Library.
The expectation is that some of these features will reveal a substantial difference
between customers that churn versus those that don't. This information is used to create
useful features for a classification model for churn. We will experiment using models
such as Logistic regression, random forest, gradient boosting, and decision trees to
evaluate the problem.
The classification model is evaluated using standard metrics for binary output data -
accuracy and F1-score. F1-score is given greater importance from an interpretation
perspective due to the imbalanced nature of the output data Accuracy only works well
when the dataset classes are balanced
The data we have is that of user events. Every interaction of every user with the
application is given to us. This means every time a user goes to the Home page, listens
to a song, thumbs up a song, etc. we have an event in the data corresponding to the
same.
