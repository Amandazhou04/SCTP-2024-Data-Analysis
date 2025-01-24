# Capstone Project - Predicting Customer Churn

### Simple machine learning and data analysis 

![new customer image](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/business-idea-660085_1280.jpg)

Image by Gerd Altmann from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=660085)

[Link to dataset](https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction/data)  

Note : Credits to [Venkatesh Tantravahi](https://www.kaggle.com/venkateshtantravahi) for some of the analysis strategies used here.
## Project Overview

### Client: 
The client is a renown bank that offers various banking products in the highly competitive consumer banking sector. Client operates primarily in France, Germany & Spain.

### Current Business Problem: 
+ The client has been experiencing increasing churn rate in recent years.
+ High acquisition costs: Customer acquisition can cost up to 5X times more1 than customer retention.
+ Highly competitive banking sector. Consumers are spoilt for choice. All banks are fighting for the same pie.

### Expected Deliverables: 
+ What: Understand the variables that impact the churn rate
+ Why: To find out why do Customers churn
+ How: Based on the findings, suggest how the bank can reduce the churn rate
+ Who: Prediction if a customer will leave
+ What Next: Recommendations based on findings from this study

### Overall Workflow: 
![workflow](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/Project%20workflow.png)

<details>
<summary><b>The Dataset</b></summary>

The dataset contains <b>14 columns, 10,002 records.</b> 
It includes the following attributes:

- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)

</details>

<details>
  <summary>Visualisations</summary>
 
 Through visualisation, we are able to better understand and uncover any relationships or trends that are present in the dataset. Some visualisations include:
#### Pairplot Exploring Relationships Between Variables
![pairplot](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/pairplot.png)  

#### Distribution of Numeric Variables
![numeric variables distribution](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/distribution%20num%20variables.png)

#### Distribution of Categorical Variables
![Cat variables distri](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/distribution%20cat%20variables.png)

#### Correlation Between Features and Target - Violin Plot
![violin plot](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/violin%20plot.png)

#### Correlation Between Features and Target - Categorical Variables
![chi sq](https://github.com/Amandazhou04/SCTP-2024-Data-Analysis/blob/a57f7d0e2ca55123279b27cf05959bdbe69132d9/images/capstone%20proj/chi%20sq%20cat%20features.png)

</details>

### Key Takeaways & Recommendations:
  
#### Customised targeted campaigns by age group & country
- Majority of younger customers tend to remain with the bank, but older customers show an increased tendency to leave
- Differences in churn rates in different countries ( Lowest churn rate rate in Germany)

#### Further investigation product ownership behaviour
- Low retention rate for customers who own 3 or more products
- Additional customer survey to look into possible reasons for underperforming products/service offerings
- Additional analysis into type of product owned (Wealth/Investment-related products? Loans?) >> provide insights into banking needs or any gaps in current offerings

#### Aggressive new customer acquisition campaign
- Sharp dip in number of customers with tenure of 10 years & 0 years. This implies that there are fewer new customers in the last 1 year and a dip in number of older customers.
- Investigate reasons for low onboarding of new customers in the past year. Is it Geography specific?

#### Investigate correlation between ‘Balance’ & ‘IsActiveMember’
- Sizeable portion of the bank's customers hold zero balance in their accounts.
- Additional analysis to look into the correlation between balance amount and active/inactive member status to see if customers are purely using the account as a holding transactional account.
- Perhaps consider implementing retention campaigns to encourage more engagements and to turn them into active members, thereby increasing retention rate.


Like what you see? Get in touch with me on [LinkedIn.](linkedin.com/in/amanda-z-62110417)
