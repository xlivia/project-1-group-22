### Table of Contents

1. [Installation](#installation)
2. [Business Understanding](#business)
3. [Data Understanding](#data)
4. [Data Preparation](#preparation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Business Understanding<a name="business"></a>

Banks are the basic financial institutions, they accept deposit demands while at the same time they use it to make loans. Even if the first concept of banking may have begun in ancient Assyria and Babylonia, they have evolved a lot through the ages and still preserve a high competence for having the major numbers of clients.

Today everybody knows, at least have some basics about what it's a bank. The majority of the western citizen uses or used a bank account. But what makes a customer to stay in the bank? Many marketing experts on the field have this question and they try to understand the users behave. In this project we will try to extract from the data the behaviour of certain customers from a bank. In order to provide to the marketing department the information that they would need to better understand their customers.

To do so, we will extract the answer of the following questions from the data.

1.  Which is the impact of the education level into the income salary?
2.  Is there any influnce of the gender into the salary income?
    - Which gender is more prone to churn the bank?
3.  Higher studies implies more responsabilities with your account?
4.  Higher income implies less depts?
5.  What make a person churn the bank?

## Data Understanding <a name="data"></a>

The first thing used to get a better uderstanding of the data was the [kaggle web](https://www.kaggle.com/sakshigoyal7/credit-card-customers) page which provide us the dataset. In the web we can find a basic description of the data. But what is more important is the description of each feature from the dataset.

Once we checked all that information we can deep dive into the data a bit more through the file called DataExploration.

## Data Preparation <a name="preparation"></a>

The first thing to check while you prepare the data are the null values. We explored this in the file "DataExploration" and we discovered that all the null values from the dataset are marked as "Unknown", so we decided that could be interesting to keep those values unchanged. Then, for instance in a situation where we are analysing the salary we can analyse also the number of "Unknown" values.

## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions (ChurnQuestion, DeptsQuestion, SalaryQuestions). Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells were used to assist in walking through the thought process for individual steps.

There is also a file with an exploration of the data. (DataExploration)

The file 'BankChurners.csv' is the data set used to anserw the questions.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://cmdraghici.medium.com/how-bank-clients-behave-442910aa3635).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/sakshigoyal7/credit-card-customers).  Otherwise, feel free to use the code here as you would like! 