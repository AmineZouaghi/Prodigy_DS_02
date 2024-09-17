# 🚢 Titanic Data Analysis: Advanced Data Cleaning, Feature Engineering, and EDA

## 📋 Project Overview
This repository contains a complete data analysis of the Titanic dataset using advanced techniques for data cleaning, feature engineering, and exploratory data analysis (EDA). We also used machine learning (Random Forest) to assess feature importance.

The main components of this project include:
- **Data Cleaning**: Imputing missing values, handling outliers, and dropping irrelevant features.
- **Feature Engineering**: Creating new features like `FamilySize`, `IsAlone`, and extracting `Title` from the names.
- **Exploratory Data Analysis**: Visualizing the survival rate based on various features and analyzing the relationships between variables.
- **Machine Learning**: Using Random Forest to determine feature importance.

---

## 📂 Folder Structure
- **titanic_data_analysis.ipynb**: The main notebook that contains all the code, data cleaning, feature engineering, EDA, and model fitting.
- **data/titanic.csv**: The Titanic dataset (or provide a link to Kaggle if necessary).
- **images/**: Contains any plots or visualizations generated during the analysis, e.g., correlation matrix and feature importance.

---

## 📈 Key Insights
1. **Survival Rate by Gender**: Females had a significantly higher survival rate than males.
2. **Survival Rate by Class**: Passengers in 1st class had the highest survival rate, while those in 3rd class had the lowest.
3. **Feature Importance**: The most important factors for survival prediction were `Sex`, `Pclass`, and `Fare`.

---

## 💻 How to Run the Code
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-data-analysis.git
