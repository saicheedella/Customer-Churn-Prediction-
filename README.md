Customer Churn Prediction using Deep Learning
Developed a deep learning-based churn prediction model to identify whether a customer is likely to continue or exit, enabling proactive retention strategies for businesses.

📌 Project Overview

Dataset: 10,000 customer records from Spain, Germany, and France.

Goal: Predict whether a customer will take insurance or not (Exited column).

Key Features Used:

CustomerId, CreditScore, Gender, Age, Tenure, Balance

NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary

Encoded location data (Geography_France, Geography_Germany, Geography_Spain)

🛠 Tech Stack & Tools

Data Processing: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning / Deep Learning: TensorFlow, Keras, Scikit-learn

Model Architecture: Fully connected Artificial Neural Network (ANN) with dropout for regularization

Performance Metrics: Accuracy, Precision, Recall, F1-score

📊 Project Steps

Data Cleaning & Preprocessing – handled missing values, normalized features, and performed one-hot encoding for categorical variables.

Exploratory Data Analysis (EDA) – analyzed customer demographics, account details, and churn patterns.

Model Building – implemented a deep learning model using TensorFlow/Keras to classify churn.

Model Evaluation – achieved high accuracy with well-balanced precision/recall.

Insights – identified key churn factors such as low tenure, low credit score, and inactivity.

🚀 Outcome
The model can help insurance companies proactively engage at-risk customers, reducing churn rates and improving retention strategies.

📂 Repository Includes:

Data preprocessing scripts

EDA visualizations

Model training & evaluation code


