\# Telecom Customer Churn – Exploratory Data Analysis (EDA)



This project performs Exploratory Data Analysis (EDA) on a synthetic telecom customer dataset to analyze churn patterns, customer behavior, and feature distributions.  

The dataset is programmatically generated to simulate realistic business scenarios.



\## Project Overview



\- Generated a 50,000-record synthetic telecom dataset using Python (NumPy, Pandas)  

\- Engineered features such as age, gender, tenure, monthly charges, contract type, payment method, internet service, support calls, total charges, and churn  

\- Created a rule-based churn label to simulate real-world churn behavior  

\- Performed EDA to analyze churn trends, feature distributions, and customer segments  

\- Exported the final dataset to CSV for reporting and analytics



\## Dataset Features



\- customer\_id – Unique customer identifier  

\- age – Customer age  

\- gender – Male / Female  

\- tenure\_months – Number of months with the service  

\- monthly\_charges – Monthly subscription charges  

\- contract\_type – Month-to-Month, One Year, Two Year  

\- payment\_method – UPI, Credit Card, Debit Card, Net Banking  

\- internet\_service – Yes / No  

\- support\_calls – Number of customer support interactions  

\- total\_charges – Calculated as monthly\_charges × tenure\_months  

\- churn – Binary churn label (0 = No, 1 = Yes)



\## Churn Label Logic



The churn label is generated using a simple rule-based approach:



\- Customers with:

&nbsp; - Month-to-Month contracts  

&nbsp; - High support call volume  

&nbsp; - Short tenure  



are more likely to be labeled as churned.



\## EDA Highlights



\- Data quality checks (info(), describe(), null values, duplicates)  

\- Distribution analysis of numerical features (age, tenure, charges, support calls)  

\- Categorical analysis of gender, contract type, payment method, and internet service  

\- Churn distribution and class imbalance analysis  

\- Cross-tab analysis between churn and key features  

\- Tenure-based customer segmentation  

\- High-risk churn segment identification  

\- Visualizations using Seaborn



\## Tech Stack



\- Python  

\- Pandas  

\- NumPy  

\- Seaborn  

\- Matplotlib  

\- Jupyter Notebook  



\## How to Run



1\. Clone the reposito



