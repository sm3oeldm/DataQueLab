# DataQueLab
A hands-on project demonstrating practical data cleaning and preprocessing techniques using Python.

## 📌 Overview

This project focuses on **practical data cleaning and preprocessing techniques** commonly required before applying machine learning models.  
The goal is to identify and resolve real-world data quality issues, transform raw features into usable formats, and validate preprocessing choices through exploratory analysis.

The project is implemented in Python using Jupyter notebooks and emphasizes **understanding why each preprocessing step is necessary**, not just how to apply it.

---

## 🎯 Objectives

- Identify and analyze missing data
- Clean and standardize raw datasets
- Transform features to improve usability and distribution
- Compare preprocessing techniques and their effects
- Prepare datasets for downstream machine learning tasks

---

## 🧹 Data Cleaning Tasks Performed

### 1️⃣ Missing Value Analysis
- Detected missing values across multiple features
- Quantified missingness to understand data quality
- Applied appropriate handling strategies depending on the context

### 2️⃣ Date and Time Processing
- Parsed raw date strings into proper datetime formats
- Extracted meaningful temporal information
- Ensured consistency across time-based features

### 3️⃣ Feature Scaling and Transformation
- Applied **Min-Max scaling** to normalize feature ranges
- Used **Box-Cox transformations** to reduce skewness and stabilize variance
- Compared transformed vs original distributions

### 4️⃣ Exploratory Data Analysis (EDA)
- Visualized feature distributions before and after transformations
- Validated preprocessing decisions through plots and summary statistics
- Ensured data consistency and readiness for modeling

---

## 📊 Techniques Demonstrated

- Handling missing data
- Feature scaling vs normalization
- Distribution transformation
- Exploratory data analysis
- Data validation for ML pipelines

---

## 🧪 Tools and Technologies

- **Python**
- **Pandas**
- **NumPy**
- **SciPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📁 Project Structure

├── Lecture01.ipynb # Missing values and basic cleaning
├── Lecture02.ipynb # Date/time handling and preprocessing
├── Lecture03.ipynb # Scaling, normalization, and transformations
└── README.md


---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy scipy matplotlib
