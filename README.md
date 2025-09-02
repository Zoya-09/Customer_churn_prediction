# 📊 Customer Churn Prediction

# 🚀 Project Overview
- This project focuses on building and evaluating machine learning models to predict customer churn using classification techniques. 
- Performed Exploratory Data Analysis.
- Applied multiple classification models 
- Compared models using Accuracy, Precision, Recall, and F1-score.

# 🧩 Dataset
📂 Dataset Source: *https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset*
- The dataset includes customer attributes such as:
- Subscription type
- Contract length
- Demographics (age, gender)
- Churn status (Target variable: 0 = Not churned, 1 = Churned)

# 📌 Key Insights
- Random Forest and XGBoost achieved the best results (~93% accuracy).
- Logistic Regression was less effective due to dataset complexity.
- Feature correlation analysis showed no strong multicollinearity.

# 🛠️ Tech Stack
- Python
- Pandas & Numpy
- Matplotlib, Seaborn and Plotly
- Scikit-learn
- XGBoost

# ✨ Future Improvements
- Perform hyperparameter tuning for further optimization.
- Add SHAP/Feature importance analysis for interpretability.
- Try deep learning approaches like ANN or LSTM for sequential behavior analysis.
- Deploy best model (Random Forest/XGBoost) as an API or web app.
