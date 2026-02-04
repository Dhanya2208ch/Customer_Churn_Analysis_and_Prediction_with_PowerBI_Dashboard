## 🚀 Customer_Churn_Analysis_and_Prediction_with_PowerBI_Dashboard
```
An end-to-end Machine Learning + Business Intelligence project that predicts customer churn for a music streaming platform and delivers actionable insights through an interactive Power BI dashboard.

The system helps businesses identify at-risk customers early, understand why they churn, and take data-driven retention actions to reduce revenue loss.
```

### 🎯 Project Overview
```
Customer churn directly impacts subscription-based platforms by increasing acquisition costs and reducing long-term revenue.

### This project:

✔ Detects customers likely to churn using Machine Learning
✔ Analyzes behavior and engagement patterns
✔ Segments customers by risk level
✔ Visualizes insights with Power BI
✔ Enables targeted retention campaigns
```

### 📈 Key Results
```
✅ Model Accuracy: 87.2%
✅ ROC-AUC Score: 0.89
✅ 128 high-risk customers identified
✅ Actionable retention strategy enabled through dashboard insights
```

### 📊 Dataset
```
Source: Kaggle – Spotify Customer Churn Dataset
Size: 500+ customers
Features: 10+

### Features include:

Customer demographics (country, subscription type)
Usage behavior (daily minutes, playlists, genres)
Engagement metrics (skips, support tickets, last login)
Target variable: churned (0 = Active, 1 = Churned)
```

### 🛠️ Technologies Used
```
### Machine Learning
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

### Business Intelligence
Power BI

### Development
Visual Studio Code
Jupyter Notebook
```

### 🔄 Methodology
```
Data Cleaning - Handle missing values and quality issues
EDA - 6 visualizations analyzing churn patterns
Feature Engineering - Created 5 new features (engagement_score, activity_level, etc.)
Model Training - Compared 4 algorithms (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting)
Evaluation - Selected Random Forest based on accuracy and ROC-AUC
Risk Segmentation - Categorized customers into Low/Medium/High risk
Dashboard - Built interactive Power BI dashboard with 15+ visuals
```

### 🔍 Key Insights
```
### Top Churn Drivers:
Days since last login (inactive users 3x more likely to churn)
Support tickets (2+ tickets increase risk by 65%)
Low daily usage (< 30 minutes)
Free subscription type (2x higher churn rate)
High skip rates (indicates dissatisfaction)
```

### 💼 Business Impact
```
### This solution helps the business:
Target 128 high-risk customers
Re-engage inactive users (15+ days)
Improve customer support experience
Convert free users to premium
Reduce churn & increase revenue
```

### 📊 Power BI Dashboard Features
```
KPI Cards: Total Customers, Churn Rate, Model Accuracy, High Risk Count
Charts: Churn by subscription, risk distribution, country map, genre analysis
Filters: Subscription type, country, risk level, genre
Table: High-risk customers for immediate action
```

### 📁 Project Structure
```
Customer_Churn_Analysis_and_Prediction_with_PowerBI_Dashboard/
├── spotify_churn_dataset.csv
├── data.ipynb
├── spotify_churn_predictions_final.csv
├── visualizations (4 PNG files)
├── Spotify_Dashboard.pbix
└── README.md
```

### 🚀 Getting Started
```
# Clone repository
```git clone https://github.com/Dhanya2208ch/Customer_Churn_Analysis_and_Prediction_with_PowerBI_Dashboard.git```

# Install dependencies
```pip install pandas numpy matplotlib seaborn scikit-learn```

# Run VS code
```data.ipynb```

# Open Power BI Dashboard
Open Spotify_Dashboard.pbix in Power BI Desktop
```

### 👨‍💻 Author
```
Dhanya Chansoria
GitHub: https://github.com/Dhanya2208ch
LinkedIn: https://www.linkedin.com/in/dhanya-chansoria-b22b84325/
```
