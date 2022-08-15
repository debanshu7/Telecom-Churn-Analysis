# Telecom-Churn-Analysis

Dataset Info: Sample Data Set containing Telco customer data and showing customers left last month

## Insights  :

SeniorCitizen is actually a categorical hence the 25%-50%-75% distribution is not propoer

75% customers have tenure less than 55 months

Average Monthly charges are USD 64.76 whereas 25% customers pay more than USD 89.85 per month

Data is highly imbalanced, ratio = 73:27.

So we analyse the data with other features while taking the target values separately to get some insights.

Total Charges increase as Monthly Charges increases as expected.

Churn is high when Monthly Charges are high

Higher Churn is seene at lower Total Charges. However if we combine the insights of 3 parameters i.e. Tenure, Monthly Charges & Total Charges then the picture is bit clear 

Higher Monthly Charge at lower tenure results into lower Total Charge. Hence, all these 3 factors viz Higher Monthly Charge, Lower tenure and Lower Total Charge are linkd to High Churn.

HIGH Churn seen in case of **Month to month contracts, No online security, No Tech support, First year of subscription and Fibre Optics Internet**

LOW Churn is seens in case of **Long term contracts, Subscriptions without internet service and The customers engaged for 5+ years**

**Factors like Gender, Availability of PhoneService and # of multiple lines have alomost NO impact on Churn**

## CONCLUSION

**Electronic check medium are the highest churners**

**Contract Type - Monthly customers are more likely to churn because of no contract terms, as they are free to go customers.**

**No Online security, No Tech Support category are high churners**

**Non senior Citizens are high churners**
