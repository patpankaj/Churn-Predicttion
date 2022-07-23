# Churn-Predicttion

## Problem Statement
This Dataset belongs to a Machine Learning Challenge hosted at Hacker Earth.

The description of the challange follows:

Predict the churn risk rate
Max. score: 100
Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period. . Every user is assigned a prediction value that estimates their state of churn at any given time. This value is based on:

User demographic information
Browsing behavior
Historical purchase data among other information
It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.

Task
Your task is to predict the churn score for a website based on the features provided in the dataset.

Data description
The dataset folder contains the following files:

train.csv: 36992 x 25
test.csv: 19919 x 24
sample_submission.csv: 5 x 2
The columns provided in the dataset are as follows:

Column name Description

customerid-Represents the unique identification number of a 
customer Name -Represents the name of a customer 
age Represents- the age of a customer 
securityno - Represents a unique security number that is used to identify a person
regioncategory- Represents the region that a customer belongs to 
membershipcategory - Represents the category of the membership that a customer is using
joiningdate Represents - the date when a customer became a member
joinedthroughreferral - Represents whether a customer joined using any referral code or ID 
referralid - Represents a referral ID
preferredoffertypes - Represents the type of offer that a customer prefers
mediumofoperation - Represents the medium of operation that a customer uses for transactions
internetoption - Represents - the type of internet service a customer uses
lastvisittime - Represents the last time a customer visited the website
days since lastlogin - Represents the no. of days since a customer last logged into the website
avgtimespent - Represents the average time spent by a customer on the website
avgtransactionvalue - Represents the average transaction value of a customer
avgfrequencylogindays - Represents the no. of times a customer has logged in to the website
pointsinwallet - Represents the points awarded to a customer on each transaction used 
specialdiscount - Represents whether a customer uses special discounts offered 
offerapplicationpreference - Represents whether a customer prefers offers 
pastcomplaint - Represents whether a customer has raised any complaints
complaintstatus - Represents whether the complaints raised by a customer was resolved
feedback - Represents the feedback provided by a customer 
churnriskscore[Target Variable] - Represents the churn risk score that ranges from 1 to 5 
Evaluation metric score = 100 x metrics.f1score(actual, predicted, average="macro")
