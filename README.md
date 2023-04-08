# project-1-group-22

### Table of Contents
1. [Purpose Statement](https://github.com/xlivia/project-1-group-22/tree/olivia-code#purpose-statement)
2. [Questions To Answer](https://github.com/xlivia/project-1-group-22/tree/olivia-code#questions-to-answer)
3. [Bank Churners Analysis By Age](https://github.com/xlivia/project-1-group-22/tree/olivia-code#bank-churners-analysis-by-age)
4. [References](https://github.com/xlivia/project-1-group-22/tree/olivia-code#references)

## Purpose Statement
The purpose of our project is to analyse the credit card customer.
We are currently looking to analyse who is going to get churned so the financial institution can proactively go to the customer to provide them better services and turn customers’ decisions in the opposite direction.
We are planning to use Kaggle for our Credit Card Customer data and use different sources to get information for power point.

## Questions To Answer
1. What is the overall customer churn rate, and how does this vary by demographic factors such as age?
2. What are the most common reasons that customers churn, and what factors are most strongly associated with customer retention?
3. What types of credit card products or features are most strongly associated with customer retention, and how can these be optimized to improve customer satisfaction and reduce churn?
4. What are the key indicators that signal a credit card customer is likely to churn, and how can these be identified and tracked over time?
5. What strategies can a financial institution use to proactively engage with customers who are at risk of churning, and what specific actions can be taken to improve customer retention?
6. What role can data analytics play in identifying potential revenue opportunities and improving overall profitability for the financial institution?

## Bank Churners Analysis By Age
```BankChurnersAgeAnalysis.ipynb``` file analyzes the data from ```BankChurners.csv``` by age.
1. The entire dataset is loaded from the ```BankChurners.csv``` file
2. Only care about the ```Attrited Customers``` in the ```Attrition_Flag``` column so we filter out the rest.
3. Define the age groups, copy the filtered dataset to modify, and count the age groups of ```Attrited Customers```
4. Plot the count of each age group into a bar graph
5. Plot the highest age group ```40-49``` into a pie chart by ```Gender```

## References
The Dataset used for this analysis can be found [here](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?select=BankChurners.csv)