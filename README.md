🚕 NYC Taxi Fare Prediction – Automatidata Case Study
An end-to-end Data Analytics, Machine Learning, Tableau & Power BI project

By: Akash Raj

⭐ Project Overview

This project builds a complete NYC Taxi Fare Prediction System using machine learning (Random Forest), statistical diagnostics, and business intelligence tools (Tableau + Power BI).
It was developed as part of the Google Advance Data Analytics Project, combining:

Python (EDA, cleaning, modeling, prediction)

Tableau (Model evaluation on testing data)

Power BI (Operational insights + business decisions)

Business-focused reporting & case study

The goal is to help riders, drivers, and regulators understand fare behavior with greater accuracy and transparency.

🧹 Data Preparation

Performed in Python:

Removed unrealistic distances (0 or negative)

Removed negative/invalid fares

Removed incorrect durations

Engineered features:

Duration (minutes)

Distance Band

Fare Band

Time of Day

Error & Absolute Error

Model-ready and BI-ready datasets were exported as CSV.

🤖 Machine Learning Model

Model: Random Forest Regression
Performance:

Metric	Score
R²	0.974
MAE	0.43
RMSE	1.71

OLS was used only for statistical diagnostics.
Random Forest selected due to strong non-linear relationships.

📊 Tableau (Model Evaluation)

Tableau was used to analyze model performance on the testing dataset, including:

Actual vs Predicted scatter

Fare distribution

Duration vs Distance

Error analysis

Outlier detection for long-distance trips

Tableau helped validate model behavior before final BI reporting.

📈 Power BI Dashboard (Business Intelligence Layer)

The final BI dashboard includes:

KPI Cards

Actual vs Predicted Visualization

Absolute Error Breakdown

Distance Band and Fare Band Analysis

Payment Type Insights

Time of Day Insights

Decomposition Tree

The dashboard supports decision-making for operations, pricing, and anomaly monitoring.

💡 Key Insights

Long-distance trips (>20 miles) create the highest prediction variance.

Medium-distance trips (5–20 miles) are most stable and predictable.

High-fare trips (80–100 & 100+) show large fare fluctuations.

Duration is a critical driver of fare uncertainty.

Only credit card users provide tips, making them the most profitable segment.

🛠️ Actionable Recommendations

Promote credit card payments to increase driver earnings.

Implement QC rules to detect distance and duration anomalies.

Introduce upfront pricing for long-distance rides.

Improve peak-hour fleet allocation.

Build promotions for the stable, medium-fare rider segment.

📄 Final Deliverables

All project deliverables are included in the /reports folder:

✔ Full Case Study
✔ 7 Report of Progress
✔ Tableau Dashboard
✔ Power BI Dashboard
✔ Cleaned Datasets
✔ Random Forest Model

📬 Author

Akash Raj
Data Analyst | Machine Learning | Business Intelligence
