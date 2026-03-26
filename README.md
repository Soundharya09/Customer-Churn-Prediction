# 📉 Customer Churn Prediction Using Machine Learning
## 📌 Project Overview
Customer churn is a critical challenge for subscription-based businesses.

This project builds an end-to-end machine learning pipeline to predict customer churn and identify key factors contributing to customer attrition.

The goal is to help businesses proactively retain customers by using data-driven insights.

This project uses separate training and testing datasets to ensure proper model evaluation.

## 🎯 Objectives
- Analyze customer behavior and churn patterns
- Perform exploratory data analysis (EDA)
- Engineer and preprocess features
- Build and compare machine learning models
- Evaluate models using appropriate metrics
- Derive actionable business insights

## 📊 Dataset
- Two datasets are used in this project:
  - `customer_churn_dataset-training-master.csv`
  - `customer_churn_dataset-testing-master.csv`
- The datasets contain customer demographic, subscription, and usage information
- Target variable: **Churn** (1 = Churned, 0 = Retained)
- Includes both numerical and categorical features

## 🛠️ Technologies & Libraries
- Python - Programming Language
- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Data visualization
- Scikit-learn – Machine learning models & evaluation

## 🔍 Exploratory Data Analysis (EDA)
Key analyses performed:
- Churn distribution analysis
- Churn rate by contract length
- Feature correlation analysis
- Identification of high-risk customer segments

## ⚙️ Data Preprocessing
- Converted categorical variables into numerical format using one-hot encoding
- Standardized numerical features to ensure consistent model performance
- Split data into training, validation, and testing sets for reliable evaluation
- Ensured feature consistency between training and testing datasets after encoding

## 🤖 Models Implemented
- Logistic Regression
- Random Forest Classifier

Both models were evaluated and compared using:
- Accuracy
- Precision
- Recall
- ROC-AUC Score
- Confusion Matrix
- ROC Curve Visualization

## 📈 Model Evaluation
- ROC curves were plotted for model comparison
- Random Forest achieved a strong predictive performance
- Feature importance analysis highlighted key churn drivers

## 💡 Key Business Insights
- Customers with short-term or month-to-month contracts show higher churn rates
- Certain subscription types are more prone to churn
- Contract duration and service usage play a major role in retention

## 🧠 Conclusion
This project demonstrates how machine learning can be applied to:
- Predict customer churn effectively
- Identify high-risk customers
- Support business decisions with actionable insights

## ▶️ How to Run the Project
1. Clone the repository

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Open the notebook:
   ```bash
   Customer Churn Prediction.ipynb

4. Ensure the following files are in the same directory:
   - customer_churn_dataset-training-master.csv
   - customer_churn_dataset-testing-master.csv
     
5. Run all cells sequentially

## 👤 Author

#### Soundharya Sundaram Iyer
#### Aspiring Data Scientist / Passionate about Machine Learning 

### 📌 Feel free to connect with me on LinkedIn and explore more projects on GitHub.
LinkedIn : https://www.linkedin.com/in/soundharyaiyer09

Github : https://github.com/Soundharya09

### If you like this project, feel free to ⭐ star it!!!!!
