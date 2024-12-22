# mLphase-3-project
# SyriaTel customer churn prediction


### Introduction
SyriaTel is a prominent telecommunications company. It is experiencing a challenge of high customer churn. In order to mitigate financial losses and ensure the organization's long-term stability, we are tasked to create a model that predicts customers' churn through the identification of related patterns and influential factors. Consequently, the company can proactively implement strategies informed by these findings to preserve its customer base and ensured sustained growth.

### Business problem
The telecommunications industry is highly competitive, and SyriaTel is facing challenges related to customer churn, which can significantly impact the company's growth and financial stability. Each customer disconnection not only represents a loss but also poses a threat to the company's long-term success. By analyzing the factors and patterns driving churn, and developing an effective classification model to predict customer attrition, SyriaTel can take proactive steps to retain its customers and secure its future success.


### Objective
To construct a predictive model using the available dataset to categorize customers as either having churned or remained with the company.
To evaluate the model performance using appropriate/reliable evaluation metrics such as accuracy, precision, recall, and F1-score.
To identify any noticeable patterns or trends linked to customers' churn.
To identify the specific features that have a significant impact on the customer churn rate in SyriaTel, provide valuable recommendations based on the findings hence help to mitigate churn rates in the company and improve customer retention.


### Project's Metric of Success
The project seeks to build a machine learning model with an accuracy score of above 75%.


### Data analysis
In this section we analyzed the relationship between churn rate and various variables provided in our data and plot graphs that visualized the findings.
We checked for subscription against churn rate. We noted clients who have subscribed to international plans have higher churn rate than those without such plans, indicating that international plan users are more likely to leave. Clients who do not have voice mail plans experience a significantly higher churn rate compared to those who are subscribed to voice mail services, suggesting that the lack of this feature may contribute to dissatisfaction and increased attrition.

We also did analysis on some of the numerical variables which showed a strong correlation between the total day, evening, and night charges, and a higher churn rate. However, this relationship is not as apparent with the international charge rate. Additionally, a higher number of customer service calls tends to be associated with an increased churn rate. 


### Modelling
In this section we modeled our sets using Logistic regression, Random forest and K-Nearest Neighbour
We  improved on the random forest model as it had the highest level of accuracy and prediction
The model is excellent at identifying non-churned customers, with high precision 0.96 and recall 0.97. This means the model correctly classifies almost all non-churned customers.F1-Score is 0.97 this shows Excellent balance between precision and recall
The model performs well on churned customers as well with a precision of 0.83 and a recall of 0.79 which is an improvement from the previous score of 0.67 improved. F1-Score is now at 0.81 which suggests a good balance between precision and recall, though slightly lower than for the non-churned class
The Accuracy was maintained at 94%
This tuned model is highly effective in identifying churned customers and is well-suited for the project objective of maximizing the identification of churned customers to gain insights into the reasons for churn and customer behavior patterns. The accuracy is also greater than the project's metric of success which was set at an accuracy of 75%.


### Recommendations
The company should look into the charges. There is a strong correlation between the total day, evening, and night charges, and a higher churn rate.
The company should equip their contact center with the necessary tools and resources to ensure that customer service interactions are satisfying, as a higher number of customer service calls tends to be associated with an increased churn rate. By improving the quality of customer service and addressing issues effectively, the company can reduce the likelihood of customer attrition.
This Random Forest model, after hyperparameter optimization, achieves high overall performance and strikes a good balance between identifying churned and non-churned customers. It is well-suited for deployment in the churn prediction system, but ongoing monitoring and periodic retraining are recommended to maintain performance over time.























