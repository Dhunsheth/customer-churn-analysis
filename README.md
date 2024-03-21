# Customer Churn Analysis   

[Report Link](https://dhunsheth.github.io/customer-churn-analysis/)

## Introduction    
The project will aim to analyze churn data from an Iranian telecommunications company. The goal is to understand
the relationship between customer interactions/profiles to the rate at which customers churn. By modeling this
relationship, the company can then predict the expected reduction in the number of customers that churn based on
some reduction in call failures or complaints.     

**Statistical Description**    
The dataset we are using is publicly available from the UC Irvine Machine Learning repository. Data was randomly
collected from an Iranian telecom company database over a period of 12 months in 2020. The database has a total of
3150 rows, each representing a customer. The following are the 13 columns in the database:

- Call Failures (numerical): the number of call failures over 9 month period
- Complains (binary): 0: No complaint, 1: complaint
- Subscription Length (numerical): total months of subscription
- Charge Amount (ordinal): 0: lowest amount, 9: highest amount
- Seconds of Use (numerical): total seconds of calls over 9 month period
- Frequency of use (numerical): total number of calls over 9 month period
- Frequency of SMS (numerical): total number of text messages over 9 month period
- Distinct Called Numbers (numerical): total number of distinct phone calls
- Age Group (ordinal): 1: younger age, 5: older age (10-19 is 1, 20-29 is 2, etc.)
- Tariff Plan (binary): 1: Pay as you go, 2: contractual
- Status (binary): 1: active, 2: non-active
- Customer Value (numerical): The calculated value of customer 9 month period
- Churn (binary): 1: churn, 0: non-churn - the state of the customers at the end of 12 months

All of the attributes except for churn is aggregated data of the first 9 months. The churn labels are the state of the
customers at the end of 12 months. The three months is the designated planning gap.

**Potential Supplementary Analysis**
Additional questions to be answered include:
1. Is there any collinearity between predictors?
2. What is the expected reduction in churn if a proposed business solution can reduce call failures by 50%?
3. Which predictors dominate churn for high-value customers?
   
**Dataset Reference:**     
[1] Iranian Churn Dataset. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5JW3Z.
