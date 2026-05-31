# Machine Failure Prediction (Predictive Maintenance)

## Overview
Unplanned machine failures can lead to high operational costs and downtime.  
This project focuses on predicting machine failures in advance using machine learning techniques based on sensor data.

## Dataset
The dataset contains real-world industrial sensor data with features such as:
- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

Target variable:
- Machine failure (0 = No Failure, 1 = Failure)

## Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Models & Approach

- Exploratory Data Analysis (EDA) — identified class imbalance and key failure patterns
- Feature Engineering — selected most predictive sensor features
- Model Training — trained and compared multiple classifiers
- Evaluation — assessed using precision, recall, F1-score, and AUC-ROC

## Key Takeaways

- Tool wear and torque were the most significant predictors of machine failure
- Addressing class imbalance was critical to improving recall on failure cases
- The model enables proactive maintenance scheduling, reducing unplanned downtime
