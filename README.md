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
```BankChurnersAgeAnalysis.ipynb``` file analyzes the data from ```BankChurners.csv``` by age, and contains information on credit card customers of a bank.
The dataset includes various features related to customer demographics, banking behavior, and credit card usage, as well as a binary target variable indicating whether the customer has churned or not.

The data focuses on exploring the relationship between customer age and churn rate, as well as other demographic factors and their impact on churn rate.
The data groups customers into age groups and calculates the churn rate for each group.
The results show the highest and lowest churn rates among customers in each age group.

The data also examines the relationship between churn rate and other demographic factors such as income, education level, and card category.
The results show that churn rate is typically lower among customers with lower income levels and educational attainment, as well as among customers with lower-tier credit card categories.

Overall, this analysis provides insights into the factors that influence churn rate among credit card customers focusing on how age affects churn rate.
The findings suggest that age, with respect to income, education level, and card category are important predictors of churn rate, and that targeting marketing and retention efforts towards specific demographic groups may be an effective strategy for reducing churn rate and increasing customer loyalty.

- The age group with the highest churn rate is people aged 50-59, in the Platinum card category, with a churn rate of 37.5%
- The age group with the lowest churn rate is people with a 0% churn rate are:
    - Age Group: 18-29; Income: $80K - $120K
    - Age Group: 18-29; Card Category: Gold
    - Age Group: 18-29; Card Category: Silver
    - Age Group: 30-39; Card Category: Platinum
    - Age Group: 60+; Card Category: Gold

## References
The Dataset used for this analysis can be found [here](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?select=BankChurners.csv)