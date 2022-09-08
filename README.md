# Customers-Churn-Model
Building a predictive churn model based on a dataset of a telecommunication service provider

This is the repository for a data challenge Challenge, where I performed EDA, data visualisation and I compared and evaluated some classification models.

## Content
- [Tasks](#Task)
- [Workflow](#Workflow)
- [Insights and Conclusions](#Insights-and-Conclusions)
- [In the repository](#In-the-repository)

## Tasks

Q1) Build a churn model with the following data. 
In your submission, please include all code, any Exploratory Data Analysis, model comparison, evaluation etc. 
Please also include a presentation deck (no more than 10 slides) presenting the results and insights of the analysis to a business audience. 
 
Q2) Imagine you have $100,000 for marketing purposes, how and where would you invest the money (e.g. email campaign, billboard ads etc). How will you measure the success (return of investment) of the marketing budget?

## Workflow

- Data exploration
- Data Visualisation
- Feature Engineering
- Data Preprocessing 
- Models comparisons and evaluations

## Insights and Conclusions

We can divide the dataset into three main parts:
- Customers details and demographics,
- Subscribed services,
- Relative Fees and Tenure months.

Problem: The target variable (Churn: Yes / No) is not balanced. This has to be keept in mind when choosing and evaluating the ML model.

Using the appropriate ML classifier for an unbalanced dataset, we were able to correctly predict 84% of the churning customers
Looking at the weight that each feature in the dataset had on the best performing model, we can infer that:
type of contract, having dependents and tenure are the top 3 reasons of churn.
These results confirm what outlined in the exploratory analysis of the dataset and from the reasons of churn when present in the dataset.
As a suggestion to improve the business model, we can suggest to be more competitive in the contract offers, especially for the internet services and to privilege those customers who have dependents.

## In the repository

- [Data](https://github.com/clastanga/Customers-Churn-Model-/tree/main/Data) that contains the starting dataset
- [Notebook](https://github.com/clastanga/Customers-Churn-Model-/blob/main/Yara_Churn_Model_EDA_Data_Visualisation_Models_Evaluation.ipynb) that contains the code used to explore, analyse, visualise and build the ML models.
- [Presentation](https://docs.google.com/presentation/d/1V_ik_9HuHu4-MNKwJZsuw3bdlm_dP9zzkv_adcjOfl8/edit#slide=id.g15127ee6982_0_334) where the main outcomes are presented and organized for a business audience, plus the answer to Q2.

