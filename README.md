# Customer Churn Prediction - Machine Learning Project
This project is focused on predicting customer churn using machine learning algorithms. The goal is to analyze historical customer data and build a predictive model that can identify customers who are likely to stop using a service soon.
## Problem Statement
Customer churn is a critical metric for businesses, especially in telecom, subscription, and SaaS industries. Retaining existing customers is often more cost-effective than acquiring new ones. This project uses classification models to predict whether a customer will churn based on features like usage, customer service interactions, tenure, and payment behavior.
## Project Structure
prediction-customer-churn-machine-learning-project/ │ ├── dataset/ │ └── customer_churn_data.csv # Cleaned dataset │ ├── notebook/ │ └── churn_prediction.ipynb # Jupyter Notebook with full EDA + ML │ ├── models/ │ └── README.md

##  Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Matplotlib (Data Visualization)
- Scikit-learn (Model building & evaluation)
- Jupyter Notebook

## ML Workflow

1. Data Preprocessing
   - Null value treatment
   - Label encoding
   - Feature scaling

2. Exploratory Data Analysis (EDA)
   - Churn distribution
   - Correlation heatmaps
   - Customer demographics and service usage

3. Model Training
   - Logistic Regression
   - Decision Tree
   - Random Forest

4. Evaluation Metrics
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix
   - ROC-AUC Curve

## Results

- Best Accuracy Achieved: ~XX% (fill in based on your model)
- Top Model Used: Random Forest / Logistic Regression / etc.
- Insights Gained:
  - Tenure and contract type are strong churn predictors
  - Monthly charges have a significant impact on churn probability


##   How to Run

1. Clone the repository
   ```bash
git clone https://github.com/HarithaNair8/prediction-customer-churn-machine-learning-project.git
 cd prediction-customer-churn-machine-learning-project
• Install dependencies
pip install -r requirements.txt
• Launch the notebook
jupyter notebook notebook/churn_prediction.ipynb

# Sample Visualizations
images/confusion_matrix_rf.png
images/lead_time_performance.png
images/precision_recall_rf.png
images/churn_dist.png
images/feature_importance.png



# Author
Created by Haritha Nair

![image](https://github.com/user-attachments/assets/67cabd49-0958-4d26-87ae-a7ea93cf6919)
