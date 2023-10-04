# The project objectives 

The project aims to identify toxic comments from users, particularly those left in product reviews on an online store, for subsequent moderation. The project's objective was to train a model to classify comments as either positive or negative, with the goal of achieving an F1 metric of no less than 0.75.

# Project description
This project was centered around machine learning (ML) methodologies:
- The dataset underwent preprocessing procedures, which involved cleansing and lemmatization of textual content.
- Pertinent terminology was extracted from the lexical compositions of both toxic and non-toxic comment datasets.
- The investigation incorporated the evaluation of three distinct ML models: logistic regression, random forest, and LGBM. To address the class imbalance issue, class weighting was used.
  
 <img width="264" alt="Снимок экрана 2023-10-04 в 2 06 14 PM" src="https://github.com/evg-pol/Training_python_projects/assets/141067147/3d925e5f-3401-4131-8253-10f4f0f52719">
  
- The logistic regression model shows the best metrics.  The F1 on the test sample is 75.3 The model successfully passed the test for adequacy.
