# Bank Customer-Churn-Analysis
Understanding the customer churn rate is an important indicator for any firm. According to a Bain & Company research, increasing customer retention for existing customers by only 5% may increase a company's profitability by 25 to 95%.

![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/Untitled.png)

## **Objective**

* Finding the % of Churn Customers and customers that keep in with the active services.
* Analysing the data in terms of various features responsible for customer Churn
* Finding a most suited machine learning model for correct classification of Churn and non churn customers.


## **Dataset**
The bank customer churn data has 14 columns, called features, including 

1.row number - A unique row numbers

2.customer id - Consist of Unique customer ID

3.surname - Name of the customer

4.credit score - Credit score of each customer. Credit score is in range from

5.geography - Location of customer. There are three location - Spain, France,Germany.

6.gender -Gender of customers.

7.age - The age of each customer.

8.tenure - how long the customer is associated with the bank.

9.balance - Total balance in customer's account.

10.number of products - Total number of products purchased through the bank.

11.credit card - Whether customer holds credit card or not.

12.active member - Whether customer is an active member of bank or not.

13.estimated salary - A estimated salary of each customer. 

14.Exited - whether exited from the bank or stays.

## **Analyzing Dataset**
We then conducted an analysis of the data using Pandas, Seaborn, and Matplotlib. We can observe that there were imbalances in our dataset. Over 80% of the data points belong to the majority class, "Stays" (0), while only 20% belong to the minority class, "Exits" (1). We used SMOTE in our machine learning techniques to solve this (Synthetic Minority Over-sampling Technique). Later, more on that.

Compared to 16% of male clients, female consumers are 25% more likely to leave the bank.
Germany has the fewest clients, but they are also the most likely to abandon the bank. In our study, almost one in three German consumers quit the bank.
Customers who bought more than two products are more likely to exit a bank.

![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/churn%20rate.JPG)
![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/gender.JPG)
![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/churn_gender.JPG)
![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/churn_gender.JPG)

### **Machine learning using different model**
We tested seven different machine learning models to predict customer churn, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, K-Nearest Neighbor, Support Vector Machine and XGBoost. After feature engineering and hyperparameter tuning we selected the XGBoost model having highest accuracy of 93% for final prediction.

![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/table.JPG)

![Alt text](https://github.com/Tanya-Tandon02/Customer-Churn-Analysis/blob/main/Screenshot/model.JPG)
