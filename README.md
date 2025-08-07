# GOOGLE PLAY STORE APPS EDA 2025 – DATA ANALYSIS PROJECT

## 📌 Project Overview
This project involves an in-depth **Exploratory Data Analysis (EDA)** of the **Google Play Store Apps dataset**. The objective is to understand patterns and insights related to app ratings, pricing, categories, installs, and release trends. This EDA serves as a foundational analysis for potential machine learning or business decision-making projects related to mobile apps.

---

## 📂 Dataset
- **Source**: Kaggle – Google Play Store Apps Dataset
- **Rows**: ~10,800
- **Features**: 13 columns including app name, category, rating, installs, type (free/paid), price, size, and more.
- **File Used**: `google_cleaned.csv`

---

## 🧹 Data Cleaning Performed
- Converted data types of `Reviews`, `Installs`, and `Price` from string to integer.
- Cleaned special characters like `+`, `,`, and `$`.
- Handled missing values in `Rating`, `Size`, `Type`, `Current Ver`, and `Android Ver`.
- Filled or dropped nulls depending on context.
- Removed duplicates and unnecessary columns.

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Distribution plots of numeric features: `Installs`, `Reviews`, `Size`, `Price`, `Rating`
- Count plots for categorical features: `Category`, `Type`, `Content Rating`

### 🔹 Bivariate Analysis
- Boxplots and scatter plots to analyze:
  - Ratings across app categories
  - Free vs Paid app ratings
  - Price vs Rating (Paid apps)
  - Installs vs Rating (log scale)
  - Size vs Rating

### 🔹 Multivariate Analysis
- Strip plot of Installs by Category segmented by Free/Paid
- Boxplots comparing Ratings across Content Ratings

### 🔹 Time-Based Trends
- Number of apps released per year
- Average rating trend by year

---

## 📈 Tools and Libraries
- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Warnings** – Ignored warning messages for clean output

---

## ✅ Key Insights
- Certain categories are more saturated than others.
- Paid apps tend to have slightly higher ratings.
- Many apps are released in recent years, showing growth in the Play Store ecosystem.
- App size and price have varying correlations with rating and installs.

---

## 📅 Year
- Project conducted in **2025**

---

## 📌 Status
✔️ Completed (EDA only)  
🚫 No Machine Learning implemented in this version

---

## 🧠 Author
**Nayan** – Data Enthusiast & Aspiring Developer  
