# Project goals
The telecommunications operator  wants to learn how to predict customer churn. If it turns out that a user plans to leave, they will be offered promo codes and special conditions. The operator's team has collected personal data on some customers, information about their tariffs, and contracts.
The operator provides two main types of services:

1. Landline telephone communication. It is possible to connect a telephone to multiple lines simultaneously.
2. Internet. Connection can be of two types: through a telephone line (DSL, from English "digital subscriber line") or fiber optic cable (Fiber optic).

Additionally, the following services are available:

- Internet security: antivirus (DeviceProtection) and blocking of unsafe websites (OnlineSecurity).
- Dedicated technical support line (TechSupport).
- Cloud file storage for data backup (OnlineBackup).
- Streaming television (StreamingTV) and a movie catalog (StreamingMovies).

Customers can pay for the services every month or sign a contract for 1-2 years. Various payment methods are available, and customers can receive an electronic receipt.

**Task:**

Build a model that predicts customer churn.

**Project Metrics:**

The primary metric is ROC-AUC, and it should be higher than 0.85 on the test sample.

**Main results**

1. A basic statistical analysis was conducted, including data visualization and the construction of a correlation matrix.

![Без названия](https://github.com/evg-pol/Training_python_projects/assets/141067147/a38dcd4d-efba-413a-8357-a1776e799bb2)


2. Three ML models were analysed: the Random Forest, LGBM, CatBoost. CatBoost demostrated the best results on the train sample
 
<img width="375" alt="Снимок экрана 2023-10-20 в 6 16 27 PM" src="https://github.com/evg-pol/Training_python_projects/assets/141067147/6f7ae39a-215e-41ee-a4d9-cea91956f18f">


3.  The most important features have been selected for the CatBoost model.
    
![Без названия (1)](https://github.com/evg-pol/Training_python_projects/assets/141067147/710ea28d-5090-4d3f-9dd4-a89d6b2f6062)
  
4. The model with the selected features showed the better results

<img width="475" alt="Снимок экрана 2023-10-24 в 6 09 52 PM" src="https://github.com/evg-pol/Training_python_projects/assets/141067147/159ee84c-6eab-4695-813d-c2ff875e54f9">
