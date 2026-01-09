# 🚀 AnalyzerCustomer_Churn_Analysis_and_Prediction_with_PowerBI_Dashboard:

🎯 Project Overview
This project identifies at-risk customers for a music streaming platform using machine learning and provides actionable insights through interactive Power BI dashboards.

Key Results:

Model Accuracy: 87.2%

ROC-AUC Score: 0.89

Identified 128 high-risk customers for immediate action

📊 Dataset
Source: Kaggle - Spotify Customer Churn Dataset
Size: 500+ customers with 10 features

Key Features:

Customer demographics (country, subscription type)

Usage patterns (daily minutes, playlists, genre)

Engagement metrics (skips, support tickets, last login)

Target: churned (0 = Active, 1 = Churned)

🛠️ Technologies Used
Machine Learning: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Business Intelligence: Power BI
Environment: Visual studio code

🔄 Methodology
Data Cleaning - Handle missing values and quality issues

EDA - 6 visualizations analyzing churn patterns

Feature Engineering - Created 5 new features (engagement_score, activity_level, etc.)

Model Training - Compared 4 algorithms (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting)

Evaluation - Selected Random Forest based on accuracy and ROC-AUC

Risk Segmentation - Categorized customers into Low/Medium/High risk

Dashboard - Built interactive Power BI dashboard with 15+ visuals

🔍 Key Insights
Top Churn Drivers:

Days since last login (inactive users 3x more likely to churn)

Support tickets (2+ tickets increase risk by 65%)

Low daily usage (< 30 minutes)

Free subscription type (2x higher churn rate)

High skip rates (indicates dissatisfaction)

Business Impact:

Target 128 high-risk customers with retention campaigns

Re-engage users inactive for 15+ days

Improve support experience to reduce tickets

Convert high-engagement free users to premium

📊 Power BI Dashboard Features
KPI Cards: Total Customers, Churn Rate, Model Accuracy, High Risk Count
Charts: Churn by subscription, risk distribution, country map, genre analysis
Filters: Subscription type, country, risk level, genre
Table: High-risk customers for immediate action

📁 Project Structure
spotify-churn-prediction/
├── data/
│   └── spotify_churn_dataset.csv
├── notebooks/
│   └── Churn_Prediction_Analysis.ipynb
├── outputs/
│   ├── spotify_churn_predictions_final.csv
│   └── visualizations (4 PNG files)
├── dashboard/
│   └── Spotify_Churn_Dashboard.pbix
└── README.md

🚀 Getting Started
# Clone repository
git clone https://github.com/Dhanya2208ch/Customer_Churn_Analysis_and_Prediction_with_PowerBI_Dashboard.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn 

# Run VS code

# Open Power BI Dashboard
Open Spotify_Churn_Dashboard.pbix in Power BI Desktop
