# Comparing-Classifiers
Comparing Classifiers
Overview

The goal of this project is to predict whether a customer will subscribe to a term deposit based on various factors such as personal attributes, contact history, and economic indicators.

The dataset comes from the UCI Machine Learning Repository and was collected from a Portuguese banking institution’s telemarketing campaigns.

Key Findings

Influence of previous contacts: Customers who had successful previous campaigns are more likely to subscribe.

Economic indicators matter: Features like the Euribor 3-month rate and employment variation rate have a strong correlation with subscription likelihood.

Call duration is a strong predictor: However, it should not be used for realistic predictive models, as it is only known after a call is completed.

Class imbalance: The dataset is highly imbalanced, with a majority of customers not subscribing to term deposits.

Recommendations

Target customers with previous positive engagements to improve campaign efficiency.

Leverage economic conditions: Optimizing campaign timing based on favorable economic indicators can boost subscription rates.

Address class imbalance: Using techniques like oversampling, SMOTE, or adjusting class weights can improve model performance.

Access the Notebook

View GitHub Repository (Add link here)

Files

bank-additional-full.csv

bank-additional.csv

Conclusion

By analyzing the factors that influence term deposit subscriptions, we can conclude that targeting customers with prior positive interactions, considering economic trends, and handling class imbalance effectively can significantly enhance marketing success. These insights provide actionable strategies for banks to optimize their telemarketing campaigns and increase customer conversions.
