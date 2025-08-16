# 📊 Netflix Data Cleaning & EDA

## 📌 Project Overview
This project is part of my **7-Day Data Science Challenge (Day 1)**.  
The goal is to **clean, explore, and visualize** the Netflix Movies & TV Shows dataset to identify trends, patterns, and insights.

## 📂 Dataset
- **Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Description:** Contains information about movies and TV shows available on Netflix, including title, director, cast, country, release year, rating, and genre.

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization

## 📊 Steps Performed
1. **Data Loading & Inspection**
   - Checked dataset shape, data types, and first few rows.
2. **Data Cleaning**
   - Standardized column names.
   - Converted `date_added` to datetime format.
   - Filled missing values in `country`, `rating`, and `duration`.
   - Extracted `year_added` from `date_added`.
3. **Exploratory Data Analysis (EDA)**
   - Count of Movies vs TV Shows.
   - Top 10 genres.
   - Top 10 countries producing content.
   - Release trends over years.
   - Ratings distribution.
4. **Visualizations**
   - Bar plots, line plots, and pie charts.

## 📈 Key Insights
- Netflix has more **Movies** than TV Shows.
- The most common genre is **International Movies**.
- **United States** produces the most Netflix content.
- Significant content growth observed after **2015**.
- Most common rating is **TV-MA**.

# 📊 Global Superstore Interactive Dashboard

## 📌 Project Overview
This project is part of my **7-Day Data Science Challenge (Day 2)** and focuses on building an **interactive sales dashboard** using the Global Superstore dataset.  
The dashboard enables users to explore sales performance by category, region, and time period with interactive filters, charts, and KPIs.  
It’s designed for business stakeholders to quickly identify trends, profitable segments, and areas needing improvement.

---

## 📂 Dataset
- **Source:** [Global Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **File Used:** `Sample - Superstore.csv`
- **Description:** Contains order-level sales data including product category, sub-category, customer segment, region, shipping mode, sales, profit, and order date.

---

## 🛠 Tools & Libraries
- **Python**
- **Streamlit** – For building the interactive dashboard
- **Plotly Express** – For creating interactive charts
- **Pandas** – For data manipulation

---

## 📊 Dashboard Features
- **Filters:** Year, Region, and Category
- **KPIs:** Total Sales, Total Profit, Total Orders
- **Visualizations:**
  - Bar chart: Sales by Category
  - Line chart: Monthly Sales Trend
  - Pie chart: Profit Share by Segment
  - Geo map: Sales by Country

---
<img width="1856" height="913" alt="Screenshot 2025-08-14 154023" src="https://github.com/user-attachments/assets/98aa5eb2-31c6-4dc0-a025-20d1f281bd29" />
<img width="1094" height="493" alt="newplot (1)" src="https://github.com/user-attachments/assets/57edc2b7-661b-44f4-88da-cae23f6397a1" />
<img width="1094" height="493" alt="newplot (2)" src="https://github.com/user-attachments/assets/7bf1090b-f761-44b2-81e0-5123e3747526" />
<img width="1094" height="493" alt="newplot" src="https://github.com/user-attachments/assets/619e3a0a-8df6-4649-b8da-a9fa006926b3" />
<img width="1094" height="493" alt="newplot (3)" src="https://github.com/user-attachments/assets/cca11299-de3a-4ad4-a20f-bb7cec86da91" />


📊 Customer Churn Prediction — Day 3
📂 Dataset

Source: Telecom churn dataset

Features: Customer demographics, account details, and service usage patterns

Target: Churn (0 = Not churned, 1 = Churned)

🛠 Tools & Libraries

Python 3.9+

Libraries:

pandas, numpy → data wrangling

scikit-learn → preprocessing, models, evaluation, GridSearchCV

imblearn → SMOTE (handling class imbalance)

xgboost → Gradient Boosted Trees

matplotlib, seaborn → visualizations

streamlit → deployment (interactive web app)

🔄 Steps Performed
1️⃣ Data Preprocessing

Cleaned missing values & encoded categorical variables

Train-test split

Applied StandardScaler for feature scaling

Applied SMOTE to balance churn vs non-churn classes

2️⃣ Model Training & Hyperparameter Tuning

Random Forest: GridSearchCV optimized n_estimators, max_depth, etc.

Logistic Regression: Tuned C, penalty, solver

XGBoost: Tuned learning_rate, max_depth, n_estimators, subsample

3️⃣ Model Evaluation (Test Set Results)

📌 Random Forest (Tuned) → Accuracy: 0.76 | Recall (Churn): 0.65

📌 Logistic Regression (Tuned) → Accuracy: 0.73 | Recall (Churn): 0.69

📌 XGBoost (Tuned) → Accuracy: 0.75 | Recall (Churn): 0.66

4️⃣ Deployment Preparation

Created a Streamlit app skeleton (app.py)

Added input fields for customer data (ready for integration with trained model)

Learned how to run:

streamlit run app.py

📌 Key Insights

SMOTE improved detection of minority class (churn).

Random Forest & XGBoost offered the best balance between precision and recall.

Logistic Regression achieved the highest churn recall (69%), useful for customer retention strategies.

XGBoost (tuned) showed the best cross-validation F1 (0.84) → strong candidate for deployment.

Next Step → Build a full Streamlit app for churn prediction.

