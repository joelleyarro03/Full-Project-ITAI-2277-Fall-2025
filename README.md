README.md – Project on Predicting Student Performance

Student Performance Prediction Through Machine Learning

An All-Inclusive 16-Week Comprehensive Data Science & AI Initiative

This repository showcases my entire semester project for ITAI 2277 
Python for Generative AI, in which I created a complete machine learning pipeline aimed at analyzing
and forecasting student academic performance through regression and classification techniques.

The project covers Weeks 1 to 16, encompassing data exploration, feature engineering, model development, 
fairness assessment, visualization, and the materials for the final presentation.

## Student Performance Prediction Initiative
This initiative examines academic achievement through the application of machine learning models such as Linear Regression,
Logistic Regression, and Random Forest.

### Main Features:
- Comprehensive EDA and visualization toolkit
- Regression and Classification modeling
- Equity analysis among demographic groups
- Concluding Linear Regression model with R2 ≈ 0.89
- Compiled deliverables (models, visualizations, metrics, user manual)

### Directories:
- /notebooks
- /models
- /plots
- /final_report
- /project_package

├── notebooks/
│   └── ITAI_Full_Project.ipynb
│
├── models/
│   ├── LinearRegression_Model.pkl
│   ├── RandomForest_Classifier.pkl
│   └── LogisticRegression_Model.pkl
│
├── plots/
│   ├── Week15_MathScore_Distribution.png
│   ├── Week15_Correlation_Heatmap.png
│   ├── Week15_Actual_vs_Predicted.png
│   ├── Week15_TestPrep_Boxplot.png
│   └── Week15_FeatureImportance.png
│
├── reports/
│   ├── Final_Technical_Report.pdf   (optional)
│   └── Week14_UserGuide.txt
│
├── package/
│   ├── All exported models, plots, metrics
│
└── README.md

Project Aim
The aim of this project is to:
Examine student demographics and performance patterns
Develop predictive models for mathematics scores (regression)
Forecast pass/fail results (classification)
Conduct fairness assessments among demographic groups
Create visual representations and explanations for stakeholders
Deliver a comprehensive end-to-end AI project package prepared for deployment or demonstration

Dataset Summary
The Student Performance Dataset comprises:

gender
lunch status
test preparation course
reading score
writing score
math score (regression target)

Engineered Features:
avg_rw = average of reading and writing scores
gap_rw = difference in scores
pass_flag = 1 if the math score is 70 or above
🧠 Machine Learning Models Used
Regression (Math Score Prediction)

Linear Regression ✔ (Best Model)
Ridge Regression
Lasso Regression
Classification (Pass/Fail Prediction)
Logistic Regression
Random Forest Classifier

Visualizations (Found in /plots)
Mathematics Score Distribution
Correlation Heatmap

Actual vs. Predicted Graph
Boxplot: Test Preparation vs. Mathematics Score
Feature Importance (Random Forest)
These were utilized for the concluding presentation and technical report.

Documentation
This repository includes:
User Guide (instructions for running the notebook)
Technical Report (comprehensive project write-up)
Week-by-Week analysis within the notebook
Final Project Package containing all assets
How to Run This Project
1️⃣ Clone the repository
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Open the notebook
Run in Jupyter or Google Colab:
ITAI_Full_Project.ipynb
4️⃣ Run all cells (Kernel → Restart & Run All)
