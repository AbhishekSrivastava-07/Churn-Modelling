# PROJECT: Churn modelling
- This project was based on a bank dataset where we analyzed each variable
- to understand why customers are leaving.
- to provide incentives to certain customers to prevent them from leaving.

### Introduction:
This project is designed to explain how to use Python in a simplistic way to fuel a company’s growth by applying the predictive approach to all our actions. It will be a combination of programming, data analysis, and machine learning. We will also work hard on retaining them. That’s what makes Retention Rate is one of the most critical metrics.
Retention Rate is an indication of how good is your product market fit (PMF). If your PMF is not satisfactory, you should see your customers churning very soon. One of the powerful tools to improve Retention Rate (hence the PMF) is Churn Prediction. 


Churn quantifies the number of customers who have unsubscribed or cancelled their service contract. Customers turning their back to your service or product are no fun for any business. It is very expensive to win them back once lost, not even thinking that they will not do the best word to mouth marketing if unsatisfied.
The most important question arises is how we can predict customer churn? The basic layer for predicting future customer churn is data from the past. We look at data from customers that already have churned (response) and their characteristics / behaviour (predictors) before the churn happened. By fitting a statistical model that relates the predictors to the response, we will try to predict the response for existing customers. This method belongs to the supervised learning category, just in case you needed one more buzzing expression


### Working

We have a bank data sheet consisting of 11 parameters. Unique Id of entries is CustomerId. Then we need to understand the types of variables we have to work with. 

##### Quantitative Explanatory Variables:

•	CreditScore

•	Age

•	Tenure

•	Balance

•	NumOfProducts

•	EstimatedSalary


##### Categorical Explanatory Variables:

•	Occupation

•	Location

•	Gender

•	HasCrCard

•	IsActiveMember
 
Response Variables:  Exited

We scan the data for any missing field. Some graphs are plotted for better understanding of data.

Then test for chi-square test of independence. The Chi Square statistic is commonly used for testing relationships between categorical variables. The null hypothesis of the Chi-Square test is that no relationship exists on the categorical variables in the population; they are independent.
After running analysis for categorical variables test for relations between quantitative variables. Logistic regression is a predictive analysis used to describe data. Test for confounding. 

For better understanding of the relation we visualize the data using machine learning algorithms- decision trees and random forests. Decision Trees are a type of Supervised Machine Learning where the data is continuously split according to a certain parameter. Random Forest builds multiple decision trees and merges them together to get a more accurate and stable prediction.

To confirm the results of random forest use lasso regression. Lasso regression is a type of linear regression that uses shrinkage. Shrinkage is where data values are shrunk towards a central point, like the mean.  K-means clustering is used to test the co-relation between the clusters (data). 



