# Telco-Customer-Churn-Analysis
 The telecommunications industry is a very important industry globally which aids in communication, networking, internet connection and entertainment. However, with the advent of various telecommunications company, the need for customer retention is apparent. This analysis will highlight the causes of customer churn and present actionable insights that will aid customer gain, retention and profit maximization.

 Objectives 
The primary objective of this project is to analyze customer data to identify the drivers of churn and provide actionable recommendations that will help reduce customer attrition.
These are:
 1. Identify customer base
2. Pinpoint the segment with the highest churn.
3. Describe if contract type influence retention.
4. Find the reasons for customer churn.

Business Questions 
1. What does the customer base look like? 
2. Which segments have the highest churn? 
3. Does contract type influence retention? 
4. Does tenure affect loyalty? 
5. Which services influence churn? 
6. Which payment methods have higher churn?
7. Which actions should management take?

Key Performance Indicators
* Total customer
* total active customer 
* Total churned customers
* Customers attrition rate
* Customers retention rate 
* Average monthly subscription 
* Average yearly subscription

 Scope
The analysis focuses on historical customer records, including demographic information, account details, subscribed services, billing information, and churn status. The goal is to identify patterns and trends that explain customer behavior rather than predict future churn.

Expected Business Impact
The findings from this analysis will help the telecom company:
Reduce customer churn through targeted retention campaigns.
Improve customer satisfaction and loyalty.
Increase long-term revenue by retaining valuable customers.
Support management with data-driven decision-making.
Optimize marketing and customer service strategies.

Dataset overview 
The data is a telecommunications customer churn dataset comprising of customer information, service type, billing and churn status. The dataset contains information that will help identify customer churn rate and increase retention rate.

Data summary 
Attribute.   Description
Total row.  7044
Total column.  21
Numeric.       3
Categorical.  18
File format.    CSV

Variables
* Customer ID
* Gender 
* Senior Citizen
* Partner
* Dependents
* Tenure 
* Phone Service 
* Multiple Lines 
* Internet Service 
* Online Security 
* Online Backup 
* Device Protection 
* Tech Support 
* Streaming TV 
* Streaming Movies 
* Contract 
* Paperless Billing 
* Payment Method 
* Monthly Charges
* Total Charges
* Churn 

Data Quality Assessment 
Blanks 
There were no blank spaces or missing values in the dataset 

Duplicate 
There were no duplicate values in the dataset 

Data type
Most of the categorical data has their data type as general. Those were converted to text.
Tenure and Senior Citizen were set as general. Conversion was also made turning them into numerical values.

Consistency 
The dataset is majorly consistent with most of the categorical data bearing either "yes" or "no".

Methodology (Data cleaning)
* Categorical data stored as general were converted to text.
* Numeric data stored as general were converted to numbers.
* The dataset was checked for duplicate values and blanks.

Business Insights
 Contract type is the strongest driver of churn (43% vs 3%).
Payment method matters — electronic check churns at 45%.
Tenure and churn are moderately negatively correlated (r = -0.35).
Senior citizens churn at a notably elevated rate (42%).
Paperless billing customers churn over 2x more than others (34% vs 16%).

Business Risks
Nearly half of month-to-month, electronic-check customers may represent significant at-risk revenue.
Senior citizens churn more than expected — a currently underserved high-risk segment.
Paperless billing correlates with high churn — possibly an unaddressed experience gap.

Recommendation
 Incentivize contract upgrades — offer discounts for switching to annual/two-year plans.
Address electronic check friction — investigate issues and promote automatic payment methods.
Launch a senior-citizen retention initiative with tailored support and pricing.
Review the paperless billing experience for communication or engagement gaps.
Build an early-tenure onboarding program targeting customers in their first 12 months.
