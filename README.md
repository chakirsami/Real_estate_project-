# Real_estate_project-
📊 A data cleaning and exploratory analysis project using a housing dataset to uncover key factors affecting real estate prices. Built with Python, Pandas, and Seaborn.
# 🏠 Housing Data Analysis Project

A data analysis project focused on exploring and understanding the factors that influence housing prices. This project includes data cleaning, exploratory data analysis (EDA), and visual insights using Python libraries such as Pandas, Matplotlib, and Seaborn.

---

## 📂 Dataset

- **File name:** `Housing.csv`
- **Source:** Provided as a local dataset
- **Rows:** 545  
- **Columns:** 13 features including price, area, bedrooms, bathrooms, and more.

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning Steps

1. Renamed column names to lowercase and replaced spaces with underscores.
2. Handled missing values (none found).
3. Converted categorical `yes`/`no` features to binary (0/1).
4. One-hot encoded the `furnishingstatus` column.
5. Removed duplicate rows (if any).

---

## 📊 Exploratory Data Analysis

### Key Visuals:

- **Correlation Heatmap**: To identify relationships between variables.
- **Distribution Plot**: Shows how housing prices are distributed.
- **Scatter Plot (Area vs Price)**: Understand how area affects pricing.
- **Box Plot (Bedrooms vs Price)**: Visualize price variance across bedroom counts.

### Example Insights:

- **Area** and **number of bathrooms** are positively correlated with price.
- Houses with **air conditioning** and **basements** tend to have higher prices.
- Fully **furnished homes** are priced significantly higher on average.

---

## 📌 Project Structure

