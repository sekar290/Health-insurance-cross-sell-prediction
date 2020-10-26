# Health-insurance-cross-sell-prediction
Machine Learning using several algorithms

This is modelling that I did on Health-insurance Dataset to predict whether a customer would be interested in Vehicle Insurance. This Dataset could be find through [Kaggle!](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction?select=train.csv)

### ABOUT DATASET
This dataset contains information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc. The dataset contains categorical and numerical features with feature 'Response' as the target. Here is the description of the features:

| Variables  | Definition |
| ------------- | ------------- |
| id  | Unique ID for the customer  |
| Gender | Gender of the customer  |
| Age | Age of the customer  |
| Driving_License | 0 : Customer does not have DL, 1 : Customer already has DL  |
| Region_Code | Unique code for the region of the customer  |
| Previously_Insured | 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance |
| Vehicle_Age| Age of the Vehicle |
| Vehicle_Damage| 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past. |
| Annual_Premium| The amount customer needs to pay as premium in the year |
| PolicySalesChannel| Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc. |
| Vintage| Number of Days, Customer has been associated with the company |
| Response| 1 : Customer is interested, 0 : Customer is not interested |


### CONTEXT
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

### PROBLEM
From the context above, company would has problems to plan the communication strategy to reach out to those customers who would interested in vehicle insurance. So to minimize the finance and optimise the revenue, company needed to know whether a customers would be interested in Vehicle Insurance.

### GOAL
1. Knowing which customers tend to interested in Vehicle Insurance through Exploratory Data Analyst (EDA)
2. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

### RESULTH

#### 1. Exploratory Data Analyst (EDA)
**Here are some insight that I got from this EDA:**
- Male tend to interested in Vehicle Insurance
- Average Age of Customers who has Driving_License and Interested in Vehicle Insurance is around 43
- Customers who doesn't have Vehicle Insurance before has more high percentage of Interested in Vehichel Insurance (22.55%)
- Vehicle_Age (>2 Year) has the highest of Interested in Vehicle Insurance with around 29.37% compare to other
- Customers with Vehicle_Age >2 Years and Vehicle_Damage (Yes) has the highest percentage of Interested in Vehicle Insurance around 29.40%
- Also Customers with Vehicle_Age 1-2 Years and Vehicle_Damage (Yes) has high percentage of Interested in Vehicle Insurance around 26.68%

For more EDA regarding customers that tend to interested in vehicle insurance please kindly check on my ipynb file. I also tried explore another features and find another insight there...\

#### 2. Machine Learning
I tried several algorithm to get best model that could predict whether a customer would be interested in Vehicle Insurance.


*Please check on my ipynb file to know about the result\
thank you...*
