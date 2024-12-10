# ANN_Classification

**Dataset Overview**
The dataset includes demographic, behavioral, and financial data of customers.

**Input Features:**
CreditScore: Customer’s credit score.
Geography: Customer’s country (e.g., France, Spain).
Gender: Customer’s gender.
Age: Customer’s age.
Tenure: Duration of the customer relationship in years.
Balance: Customer’s bank account balance.
NumOfProducts: Number of products subscribed to by the customer.
HasCrCard: Whether the customer owns a credit card (Yes/No).
IsActiveMember: Whether the customer is an active bank member.
EstimatedSalary: Customer’s estimated salary.

**Output Feature:**
Exited: Target variable indicating whether the customer churned (1 = Yes, 0 = No).
This is a binary classification problem aimed at predicting whether a customer will churn based on the input features.

**Technical Highlights of the Project**

Designed an Artificial Neural Network (ANN) with:
**Input Layer**: 11 input features after preprocessing.
**Two Hidden Layers:** 64 and 32 neurons, activated using ReLU (Rectified Linear Unit).
**Output Layer:** Binary classification using sigmoid activation.
Applied **Adam Optimizer** and **binary cross-entropy loss function** for model training.
**Implemented feature engineering:**
Encoded categorical features (**Geography, Gender**) using one-hot encoding.
Scaled numerical features (**CreditScore, Balance, EstimatedSalary**) with StandardScaler for consistent feature scaling.
Achieved high accuracy in identifying potential churners, ensuring precise predictions.
Deployment:
Built an interactive web app using **Streamlit**, allowing users to:
**Input customer details dynamically.**
**Obtain real-time churn predictions from the trained ANN model.**
