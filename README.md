# **Analyzing-customer-churn-in-Power-BI**

**This project analyzes customer churn data to discover why customers are churning**

## **Churn definition**
The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop
doing business with an entity. As a result the revenue of company will not increase if existing customers are leaving the company and
get new customers is more expensive and hard that keep currently customers, so reduce churn is a priority for many companies.

One way to calculate churn can be defined by the formula:
Churn rate = customers lost / total number of customers

Understand churn help companies to:
- Measure competitiveness.
- Provides clarity of the type of customer that is leaving.


### Results
- The churn rate for the database used is **(~27%)**
- The most reason for churn is related to competitors **(~45%)**. This result demonstrates the impact of competitiveness and why maintaining the competitive edge and customer success is important for maintaining current customers.
- In California, the churn rate is abnormally high **(>60%)**

**Demographic**
- As the age increases the churn rate increase too. Over 85 years old, we observe that the churn rate is **0.52%**.

**Contract**
-  A group contract offers advantages and is generally cheaper. Comparing the group's contract we can observe that the churn rate is lower for customers who are part of a group than for those who are not. 
- Comparing annual and monthly contracts, it is also clear that customers with a monthly contract have a much higher churn rate **(46.29%)** than customers with an annual contract **(6.62%)**.

**Subscription types & Charges**
- Analyzing the churn rate from the point of view of average data consumption (GB) with downloads, we noticed that the churn rate is quite pronounced in the group of customers whose average consumption is 5 GB per month and have the Unlimited Data Plan compared to with those who don't.
- International calls vs churn rate: analyzing the data of customers who make international calls, we found that in percentage terms **72%** of customers do not have a plan and, therefore, this finding makes them potential clients for the new promotion of the international plan.
- Customer Service Call vs Churn: While the non-churned group has an average of **0.37** calls to customer service, the churned group has an average of **2.20** calls. This measure demonstrates customer dissatisfaction. Despite this result, looking specifically at the state of California, it is observed that while the percentage of churn is **63.24%**, the number of calls is on average **0.86** or **44** calls in total.
