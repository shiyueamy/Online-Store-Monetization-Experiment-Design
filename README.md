# Online Store Revenue Growth
If the EAD python notebook is not loading successfully, please visit https://nbviewer.jupyter.org/github/shiyueamy/OnlineStore/blob/master/OnlineStoreRevenue_EAD.ipynb

### Methodologies used in this project: 
Python(numpy, pandas, matplotlib,scipy,seaborn), A/B Testing, Jackknife Resampling, Exploratory Data Analyst (EDA)

### Business Objective: 
Increase store's revenue by 5%

### Workflow:
•	Performed ETL process for data preparation.
•	Developed exploratory data analysis (EDA) on online store purchasing history data to discover purchasing trends and purchasing patterns for two-week experiment period.
•	Identified a strong correlation between the performance of user conversion and the quality of added payment methods.
•	Initiated statistical experiment test on parameters impacting user conversion rate including payment methods, button click rate and purchasing behaviors during specific 7-day time frame.
•	Implemented A/B test based on hypothesis of adding first/alternative payment methods by randomly dividing consumers into two groups and analyzed revenue increase rate to validate test performance.
•	The experiment result explained a potential revenue increase by 10.7%.

### Business Insight:
During my EDA process, I found out users who had added at least one payment method show more potential to come back and make purchase within next 14 days and those who had added multiple payment methods display a relatively higher conversion rate in general. However, for the gift card users, the conversion rates between single-payment-method customers and multiple-payment-method customers present almost no difference.
For more insights please check: https://github.com/shiyueamy/Online-Store-Monetization-Experiment-Design/blob/master/Increase%20Online%20Store%20Revenue%20.pdf

### Data-driven recommendation: 
For users who unsaved payment method, reward them with a gift card or coupon code for adding a payment method to their accounts
