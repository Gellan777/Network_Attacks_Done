# 🔐 Network Attack Detection using Machine Learning
# 📌 Overview

This project focuses on detecting and classifying network attacks using Machine Learning techniques, including:

DDoS
DoS
Reconnaissance

The models are trained on the Bot-IoT dataset to identify malicious traffic with high accuracy.

# ⚙️ What was done
# 🔹 Data Processing
Merged multiple dataset files into one
Removed irrelevant columns (IDs, timestamps, etc.)
Handled missing values and duplicates
Converted data types (e.g., ports)
# 🔹 Feature Engineering
Grouped ports into categories (Well-known / Registered / Dynamic)
Reduced skewness using Log Transformation
Applied PowerTransformer for better distribution
Handled outliers to improve model performance
# 🔹 Encoding & Scaling
Used Label Encoding for the target variable
Applied Ordinal Encoding for categorical features
Used RobustScaler for feature scaling
# 🔹 Models

Two models were implemented and compared:

Random Forest
XGBoost
# 📊 Results
# ✅ Random Forest Accuracy: 99.68%
# ✅ XGBoost Accuracy: 99.71%

Both models achieved very high accuracy with strong performance across all classes.

# 📈 Key Insights
srate, proto, and flgs were among the most important features
Clear relationship between packet size/volume and attack type
DDoS attacks show significantly higher transmission rates
# 🛠️ Tools & Technologies
Python
Pandas & NumPy
Scikit-learn
XGBoost
Matplotlib & Seaborn
# 🚀 Project Goal

To build an intelligent system that can:

Detect network attacks early
Enhance cybersecurity monitoring
Support decision-making in network protection
