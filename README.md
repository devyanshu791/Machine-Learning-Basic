# Machine-Learning-Basic
This repository contains two Machine Learning programs completed.

Question 1: Student Performance Prediction (Linear Regression)
Objective
Evaluate the effectiveness of Linear Regression for predicting student final scores based on various academic and lifestyle features.
Features Used
FeatureDescriptionStudy_HoursDaily hours spent studyingAttendanceAttendance percentagePrevious_ScoresScores in previous examsSleep_HoursAverage sleep hours per nightExtracurricularParticipation in extracurricular activities (0/1)
Evaluation Metrics

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score

Output

Actual vs Predicted plot
Residual plot
Feature Coefficients bar chart

How to Run
bashpip install numpy pandas matplotlib seaborn scikit-learn
python student_performance_prediction.py

Question 2: Customer Segmentation Using K-Means Clustering
Objective
Evaluate customer segmentation quality using K-Means Clustering and various clustering metrics.
Features Used
FeatureDescriptionAgeCustomer ageAnnual_IncomeYearly income in USDSpending_ScoreScore assigned based on spending behavior (1–100)Purchase_FreqNumber of purchases per yearAvg_Order_ValueAverage value per order in USD
Evaluation Metrics

Silhouette Score — measures how similar a point is to its own cluster vs others (higher is better)
Davies-Bouldin Score — ratio of within-cluster to between-cluster distances (lower is better)
Calinski-Harabasz Score — ratio of between-cluster to within-cluster dispersion (higher is better)
Inertia — sum of squared distances to cluster centers (lower is better)

Output

Elbow Method curve
Silhouette Score vs K plot
PCA 2D cluster visualization
Annual Income vs Spending Score cluster scatter plot

How to Run
bashpip install numpy pandas matplotlib seaborn scikit-learn
python customer_segmentation_kmeans.py

Repository Structure
ml-assignment-3/
│
├── student_performance_prediction.py   # Q1 - Linear Regression
├── customer_segmentation_kmeans.py     # Q2 - K-Means Clustering
├── student_performance_output.png      # Q1 Output plot
├── customer_segmentation_output.png    # Q2 Output plot
└── README.md                           # This file

Requirements

Python 3.x
numpy
pandas
matplotlib
seaborn
scikit-learn


Author
Devyanshu
