# customer-churn-using-ML
## Customer Churn using Machine learning and Statistical analysis
In today’s world of telecommunication, it is very important for the companies to retain their customers.The objective of this report is to carry out a churn analysis which will provide insights about the customers’ behavior. Customer churn occurs when customers or subscribers stop doing business with a company or service. This dataset contains information about the customers, their tenure with the service provider, their calling pattern throughout the day along with information on the type of plan and the number of customer service calls made by them. There are several factors that determine whether that particular customer will leave or not. 
We will use logistic regression, Random forest, XGBoost algoritm to predict customer churn.

There are 3333 observations with 21 variables. Data is tidy as each variable has a column and each observation on those variables has its own row. There are no missing values and duplicate values in the data. 8 variables are numeric, 7 are integer and 6 are categorical. The brief details about the variables is given below:

1. State- State which the customer belongs to (Factor)

2. Account Length- The number of days the customer has been with the company. It has a mean of 101.1 and ranges from 1 to 243 (Int)

3. Area code -The area code of the customer’s allotted phone number (Factor)

4. Phone Number — The phone number of the customer (Factor)

5. International Plan- Whether the customer has an international plan or not (Yes-1 and No-0)

6. Voice Mail Plan- Whether the customer has a voice mail plan or not (Yes-1 and No-0) (Factor)

7. Number vmail messages- The total number of voice mails the customer gets every month (Int)

8. Total day minutes- The total number of minutes charged to the customer during the day. It has a mean of 179.8 and ranges from 0 to 350.8 (Numeric)

9. Total day calls- The total number of calls made by the customer during the day (Int)

10. Total day charge- The total amount charged to the customer during the day. It has a mean of 30.56 and ranges from 0 to 59.64 (Numeric)

11. Total eve minutes- The total number of minutes charged to the customer in evening. It has a mean of 201 and ranges from 0 to 363.7 (Numeric)

12. Total eve calls- The total number of calls made by the customer in evening (Int)

13. Total eve charge- The total amount charged to the customer in evening. It has a mean of 17.08 and ranges from 0 to 30.91.(Numeric)

14. Total night minutes- The total number of minutes charged to the customer at night. It has a mean of 200.9 and ranges from 23.2 to 395.(Numeric)

15. Total night calls- Total number of calls made by the customer at night. It has a mean of 100.1 (Int)

16. Total night charge- The total amount charged to the customer at night. It has a mean of 9.039 and ranges from 1.040 to 17.770.(Numeric)

17. Total Intl minutes- The total number of minutes charged to the customer for an international call. It has a mean of 10.24 and ranges from 0 to 20.(Numeric)

18. Total Intl calls- The total number of calls made by the customer for an international call(Numeric)

19. Total Intl charge- The total amount charged to the customer for an international call. It has a mean of 2.765 and ranges from 0 to 5.4.(Numeric)

20. Customer Service Calls- The number of calls made by the customer to the customer service. It has a mean of 1.563 and ranges from 0 to 9.(Int)

21. Churn- Whether the customer will leave the company or not (True — 1, False -0) (Factor)
