🚗 Waze User Churn Analysis
A complete Python-based data science project analyzing user behavior and churn patterns in Waze. Developed as part of the Coursera Google Adavnced Data Analytics Professional Certificate , this project simulates a real-world scenario where we uncover insights and build predictive models to understand user retention.

🎯 Project Objectives
Explore and clean Waze user data

Engineer behavioral features to support churn prediction

Compare engagement patterns between churned and retained users

Build classification models to predict churn

Communicate findings through visualizations and stakeholder-ready summaries

📁 Dataset Overview
Attribute	Description
File Name	waze_dataset.csv
Source	Provided by Coursera
Rows	2,000 users
Columns	Includes user activity metrics and churn status
Key Columns:
churn_status: Indicates whether a user has churned

drive_count, driving_days, total_km_driven: Behavioral metrics

device_type: iPhone or Android

🛠️ Tools & Technologies
Python 3.x

pandas – Data manipulation

NumPy – Numerical operations

matplotlib & seaborn – Visualization

scikit-learn – Classification modeling

Jupyter Notebook – Interactive development

🔍 Workflow Summary
1. 📥 Data Import & Initial Exploration
Loaded dataset and inspected structure

Validated column types and identified missing values

Flagged outliers in driving metrics

2. 🧹 Data Cleaning
Imputed missing values

Normalized driving metrics

Encoded categorical variables

3. 📊 Exploratory Data Analysis (EDA)
Distribution of churned vs retained users

Engagement comparisons by device type

Correlation analysis between driving behavior and churn

4. 🧪 Feature Engineering
Created new features:

km_per_drive = total_km_driven / drive_count

drives_per_day = drive_count / driving_days

Scaled features for modeling

5. 📈 Predictive Modeling
Built classification models to predict churn_status:

Logistic Regression

Decision Tree

Random Forest

Evaluated models using:

Accuracy, Precision, Recall, F1 Score

Confusion Matrix and ROC Curve

6. 📊 Visualization & Communication
Created bar charts, boxplots, and heatmaps

Summarized insights in stakeholder-friendly markdown reports

Proposed dashboard structure for executive presentation

💡 Key Insights
18% churn rate observed across the dataset

Churned users had more drives but fewer driving days, suggesting burst usage

Device type (iPhone vs Android) showed no significant impact on churn

Behavioral ratios like drives_per_day were strong predictors of churn

Random Forest model achieved highest classification accuracy (~[insert value])

🚀 Next Steps
Tune model hyperparameters for optimization

Incorporate time-based features (e.g., recency of last drive)

Deploy model via Flask or Streamlit for internal testing

Build interactive dashboard for Waze product team

📎 Repository Contents
File Name	Description
Waze_Project.ipynb	Full Python notebook with EDA and modeling
Executive_Summary.md	Business-focused summary of findings
README.md	Project documentation (this file)
waze_dataset.csv	Dataset (if permitted for sharing or linked externally)
✨ Author
Adhityan R 
