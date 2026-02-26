# 🚢 Titanic Dataset Cleaning –  Data Wrangling & Cleaning

## 📌 Project Overview
This project focuses on data wrangling and cleaning of the Titanic dataset using Python.

The objective was to:
- Handle missing values
- Encode categorical variables
- Normalize numerical features
- Create a correlation heatmap
- Export a cleaned dataset

---

## 🔍 Cleaning Performed

### Missing Values
- Age filled with median
- Deck converted to binary feature
- Embarked filled with mode

### Encoding
- Sex label encoded
- Embarked one-hot encoded
- Boolean features converted to integers

### Scaling
- Fare normalized using Min-Max scaling

---

## 📊 Correlation Heatmap Insights

- Survival positively correlates with female passengers
- Survival negatively correlates with passenger class
- Fare positively correlates with survival
- Age shows weak negative correlation

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
jupyter notebook

Open:
notebook/Titanic_Data_Cleaning.ipynb
```

---

## ✅ Final Output

- Cleaned dataset: titanic_cleaned.csv
- Heatmap image
- Fully documented notebook
- Data Quality Report included
