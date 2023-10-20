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

**Main findings**
A basic statistical analysis was conducted, including data visualization and the construction of a correlation matrix.
