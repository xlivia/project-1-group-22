# project-1-group-22

### Table of Contents
1. [Purpose Statement](#purpose-statement)
2. [Questions To Answer](#questions-to-answer)
3. [Bank Churners Analysis By Age](#bank-churners-analysis-by-age)
4. [Group Members Branches](#group-members-branches)
5. [References](#references)

## Purpose Statement
The purpose of our project is to analyse the credit card customer.
We are currently looking to analyse who is going to get churned so the financial institution can proactively go to the customer to provide them better services and turn customers’ decisions in the opposite direction.
We are planning to use Kaggle for our Credit Card Customer data and use different sources to get information for power point.

## Questions To Answer
1. What is the overall customer churn rate, and how does this vary by demographic factors such as age?
    - The Overall Churn Rate is 16.07%
    - The Overall Churn Rate by each Age Group is:

        |   Age Group   |   Churn Rate  |
        |   ----------  |   ----------  |
        |   18-29   |   8.72%   |
        |   30-39   |   14.18%  |
        |   40-49   |   16.93%  |
        |   50-59   |   16.88%  |
        |   60+ |   13.35%  |


2. What are the most common reasons that customers churn, and what factors are most strongly associated with customer retention?
    - According to age the most common reason customers churn is when they are between the ages of 40-49 with a churn rate of 16.93% followed closely behind (by less than 1%) is the age group 50-59 with a churn rate of 16.88%
    - According to age the factors most associated with customer retention is being young between the ages of 18-29

3. What types of credit card products or features are most strongly associated with customer retention, and how can these be optimized to improve customer satisfaction and reduce churn?
    - The types of credit card products in this case are the type of card which are Blue, Silver, Gold, and Platinum.
    - The age group 18-29 with the lowest churn rate have only the Blue card
    - The age group 40-49 with the highest churn rate have mostly the Gold card
    - This can be optimized to improve customer satisfaction and reduce churn by offering the Blue card, a lower rate card, and offer some reward for switching to encourage it instead of churning

4. What are the key indicators that signal a credit card customer is likely to churn, and how can these be identified and tracked over time?
    - According to age some of the key indicators that signal a customer is likely to churn is:
        - Comparing Age and Gender: Females from 18-59 are most likely to churn with a rate of 18.3%
        - Comparing Age and Education: Customers aged 40-49 with a Doctorate are most likely to churn with a rate of 25.46%
        - Comparing Age and Income: Customers aged 18-29 and 60+ who make $120K+ are most likely to churn with a rate of 33.3%
        - Comparing Age and Card Category: Customers aged 50-59 who have a Platinum card are most likely to churn with a rate of 37.5%
        - Comparing Age and Months on Book: Customers aged 50-59 who have been with the bank for 50+ months are most likely to churn with a rate of 19.86%

5. What strategies can a financial institution use to proactively engage with customers who are at risk of churning, and what specific actions can be taken to improve customer retention?
    - According to age it seems like the general profile for a customer who is likely to churn is an educated older female making a lot of money, and have had their credit card for a long time.
    - Possible strategy could be to offer a discount on rates for a period of months for long time loyalty customers to switch to a lower rate card.

6. What role can data analytics play in identifying potential revenue opportunities and improving overall profitability for the financial institution?
    - By analyzing customer data, financial institutions can gain valuable insights into customer behavior, preferences, and trends.
        - These insights can be used to identify opportunities for cross-selling additional products and services to existing customers, as well as to develop targeted marketing campaigns that are more likely to resonate with customers and drive engagement.
    - By analyzing credit card usage patterns and identifying which features and benefits are most popular with customers, financial institutions can adjust their pricing and rewards structures to better align with customer preferences and increase overall profitability.
    - The role data analytics plays can help financial institutions better understand their customers, identify potential revenue opportunities, and optimize their operations to achieve greater efficiency and profitability.

## Bank Churners Analysis By Age
```BankChurnersAgeAnalysis.ipynb``` file analyzes the data from ```BankChurners.csv``` by age, and contains information on credit card customers of a bank.

The dataset includes various features related to customer demographics, banking behavior, and credit card usage, as well as a binary target variable indicating whether the customer has churned or not.

The analysis focuses on exploring the relationship between customer age and churn rate, as well as other demographic factors and their impact on churn rate, and groups customers into age groups and calculates the churn rate for each group, to show the results of highest and lowest churn rates among customers in each age group.

The overall analysis provides insights into the factors that influence churn rate among credit card customers focusing on how age affects the churn rate.

- The age group with the highest churn rate is people aged 50-59, in the Platinum card category, with a churn rate of 37.5%
    - Age Group: 50-59; Card Category: Platinum
- The age group with the lowest churn rate is people with a 0% churn rate are:
    - Age Group: 18-29; Income: $80K - $120K
    - Age Group: 18-29; Card Category: Gold
    - Age Group: 18-29; Card Category: Silver
    - Age Group: 30-39; Card Category: Platinum
    - Age Group: 60+; Card Category: Gold

### Group Members Branches

[Muhammad Shoaib Khan's Branch](https://github.com/xlivia/project-1-group-22/tree/Muhammad-code)

[Shonna Smith's Branch](https://github.com/xlivia/project-1-group-22/tree/Shonna-code)

[Olivia Bryant's Branch](https://github.com/xlivia/project-1-group-22/tree/olivia-code)

[Sumair Rathore's Branch](https://github.com/xlivia/project-1-group-22/tree/sumair-code)

[Yumi Kim's Branch](https://github.com/xlivia/project-1-group-22/tree/yumi-code)

## References
The Dataset we used from [Kaggle](https://www.kaggle.com/) for our analysis can be found [here](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?select=BankChurners.csv)