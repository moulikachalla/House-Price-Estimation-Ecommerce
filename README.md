# 🏡 House Price Estimation on E-Commerce Platform (OLX India)

This project presents a complete data science workflow to estimate house prices using real estate listings scraped from [OLX.in](https://www.olx.in/). It includes web scraping, data cleaning, exploratory data analysis, feature engineering, and machine learning modeling.

---

## 🎯 Objective

To analyze various factors influencing house/apartment prices and develop a predictive model that can estimate prices based on key features from real-time housing listings.

---

## 🔍 Project Workflow

### 1. Data Collection
- Web scraping using **Selenium** from OLX.in for multiple Indian states.
- Extracted over **1900+ property links** with features like square footage, furnishing, floor, facing, etc.

### 2. Data Cleaning
- Handled missing values, removed outliers, and standardized column formats.
- Converted string-formatted numbers (e.g., "₹ 85,30,000") into usable numerical values.

### 3. Exploratory Data Analysis
- Performed univariate and bivariate analysis using **pandas**, **matplotlib**, and **seaborn**.
- Analyzed the distribution of price, area, and categorical features.

### 4. Feature Engineering
- One-hot encoding of categorical variables using `OneHotEncoder`.
- Extracted `state`, `city`, and `area` from location fields.
- Outlier treatment using IQR and percentile-based capping.

### 5. Modeling
- Applied **Random Forest Regressor** for price prediction.
- Split data into training and testing sets.
- Visualized model performance with scatter and distribution plots.

---

## 📈 Features Used

- `state`, `city`, `area`
- `house_type`, `sqft`, `bedrooms`, `bathrooms`
- `furnishing`, `construction_status`, `floor_no`, `facing`
- `price` (target)

---

## 🛠️ Tools & Technologies

- **Python** (Jupyter Notebook)
- **Selenium** – Web scraping
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Modeling & preprocessing
- **Joblib** – Saving encoders and models

---
## 🚀 Outcome

- Built a functional, real-world dataset from scratch using live OLX listings.
- Developed a robust regression model for price estimation.
- Visualized and interpreted patterns in real estate pricing across India.
