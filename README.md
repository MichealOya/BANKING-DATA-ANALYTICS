# BANKING-DATA-ANALYTICS
Banking customer behavior, term deposit subscription analysis and predictive modelling using Python.
# Banking Customer Behaviour and Term Deposit Subscription Analysis

## Project Overview

This project uses Python to analyse bank marketing customer data, identify factors associated with term deposit subscriptions and develop predictive models to support customer targeting.

The analysis focuses on customer behaviour, marketing campaign effectiveness and data-driven banking decisions.

## Business Objectives

- Determine the overall term deposit subscription rate.
- Identify customer segments with higher subscription rates.
- Examine the effectiveness of different contact channels.
- Investigate the relationship between previous campaign outcomes and current subscriptions.
- Develop machine learning models to predict potential subscribers.

## Dataset

- Dataset: UCI Bank Marketing
- Records analysed: 4,119
- Target variable: `y` (Yes/No)
- Key variables: Age, occupation, housing loan, contact channel, campaign contacts and previous campaign outcome.

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Key Findings

- Overall subscription rate was approximately 10.95%.
- Students recorded the highest subscription rate among occupations.
- Customers aged 55 and above had the highest subscription rate.
- Cellular contact recorded a 14.14% subscription rate compared with 5.18% for telephone contact.
- Customers with a successful previous campaign outcome recorded a 64.79% subscription rate.
- Repeated campaign contacts generally showed declining subscription rates.

## Statistical Analysis

Chi-square tests identified significant associations between subscription and contact channel, as well as previous campaign outcome.

Previous campaign outcome showed a stronger association with subscription than contact channel.

## Predictive Modelling

Logistic Regression was used to develop two classification models.

The pre-campaign model achieved:

- Accuracy: 77.43%
- Subscriber precision: 24.74%
- Subscriber recall: 52.22%
- Subscriber F1-score: 34.06%
- ROC-AUC: 0.7240

The model provides a starting point for identifying potential subscribers before marketing campaign engagement.

## Business Recommendations

1. Prioritise customers with successful previous campaign outcomes.
2. Investigate the stronger observed conversion associated with cellular contact.
3. Improve campaign targeting rather than relying excessively on repeated contacts.
4. Develop customer-specific marketing strategies.
5. Continue improving predictive models to support better marketing decisions.

## Conclusion

This project demonstrates the application of Python-based analytics and machine learning to banking customer behaviour, marketing effectiveness and predictive customer targeting.

## Project Status

Exploratory analysis and initial predictive modelling completed. Further model comparison, validation and visualisation are ongoing.
