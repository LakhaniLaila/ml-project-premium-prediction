# ml-project-premium-prediction
Health Insurance Prediction Project

🎯 Objective

Developed a machine learning model to predict health insurance costs by analyzing age, income, lifestyle, and medical history. 

🛠 Tech Stack

Python

Pandas & NumPy (data manipulation and analysis)

Scikit-learn (Linear & Ridge Regression, preprocessing, evaluation)

XGBoost

Matplotlib & Seaborn (EDA & visualization)

Streamlit (interactive web app)


⚙️ Modeling Strategy

Customers > 25 years → XGBoost for improved accuracy

Customers ≤ 25 years → Added a feature + Linear Regression to reduce errors

Combined approach delivered consistent accuracy across age groups


✨ Key Features

Generates personalized premium predictions based on user inputs

Applies tailored models (XGBoost & Linear Regression) to achieve high accuracy across demographics

