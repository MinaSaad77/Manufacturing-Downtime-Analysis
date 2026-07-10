🚀 Predictive Maintenance & Machine Failure Analysis
📌 Project Overview

This project analyzes machine sensor data to identify failure patterns, uncover root causes of machine breakdowns, and build machine learning models for failure prediction.

The goal is to support predictive maintenance strategies that reduce downtime, lower maintenance costs, and improve operational reliability.

🎯 Business Problem

Unexpected machine failures can lead to:

Production downtime
Increased maintenance costs
Reduced operational efficiency
Equipment reliability issues

This project helps identify high-risk machines before failures occur, enabling proactive maintenance decisions.

📊 Dataset Features
Feature	Description
Type	Machine type (L, M, H)
Air Temperature	Ambient air temperature
Process Temperature	Internal process temperature
Rotational Speed	Machine speed (RPM)
Torque	Applied torque (Nm)
Tool Wear	Tool wear duration
Machine Failure	Target variable
HDF	Heat Dissipation Failure
OSF	Overstrain Failure
PWF	Power Failure
TWF	Tool Wear Failure
RNF	Random Failure
🔍 Exploratory Data Analysis (EDA)

Key findings include:

Low-quality (L) machines exhibited the highest failure rate.
Heat Dissipation Failure (HDF) and Overstrain Failure (OSF) were the most common failure causes.
Tool wear showed a strong relationship with machine failures.
Rotational speed and torque demonstrated a strong inverse relationship.
Machine failures are influenced by multiple operating conditions rather than a single factor.
🤖 Machine Learning Models

The following classification models were developed and evaluated:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
ROC-AUC
💡 Business Insights
Heat-related issues are a major contributor to machine failures.
Excessive mechanical stress increases failure risk.
Monitoring tool wear can help detect failures earlier.
Predictive maintenance can significantly reduce unexpected downtime.
📈 Recommendations
Improve cooling system efficiency.
Monitor machine workload to avoid overstrain conditions.
Implement preventive maintenance schedules.
Prioritize inspection of high-risk machines.
Use machine learning predictions as an early warning system.
🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Power BI
Jupyter Notebook
BY:
AYA KHALED
NOURAN HASSAN
MALAK AMR
MARIAM MAHMOUD
PHILOPATER EMEEL
MINA SAAD
