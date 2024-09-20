# Security-Threat-Identification-using-Machine-Learning


This project focuses on identifying malware in executable files by analyzing various features extracted from their headers. Leveraging a dataset containing legitimate and malicious samples, employed machine learning techniques to build predictive models that classify files as either legitimate or malware.

Key Objectives:
Data Exploration: Perform exploratory data analysis (EDA) to understand the dataset, visualize distributions, and examine feature correlations.
Data Preprocessing: Handle class imbalance using techniques such as undersampling and scale features for improved model performance.
Model Development: Implement and evaluate multiple machine learning algorithms, including K-Nearest Neighbors (KNN), Decision Tree, and Random Forest, using grid search for hyperparameter tuning.
Performance Evaluation: Assess model accuracy, precision, recall, and F1-score, and visualize results through confusion matrices and ROC curves.
Feature Importance Analysis: Identify key features influencing model predictions, providing insights into the characteristics of malware versus legitimate files.

## Installation

Ensure you have Python installed, and then set up a virtual environment for the project.

# bash
python -m venv venv
source venv/bin/activate  
# On Windows use `venv\Scripts\activate`

pip install -r requirements.txt
