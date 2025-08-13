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

## 📸 Sample Visualizations
*(Add screenshots of your charts here for better presentation)*

## 📂 Project Structure
