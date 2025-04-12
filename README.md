# 📊 Customer Churn Data Analysis

This project presents a comprehensive **Exploratory Data Analysis (EDA)** on customer churn data. The goal is to understand customer behavior and identify factors contributing to churn (i.e., when customers stop using a service). By leveraging data visualization and analysis tools in Python, this project aims to help businesses improve customer retention and satisfaction.

---

## 🧠 Project Objective

The main objective is to explore the churn dataset to:

- Identify trends and patterns in customer churn.
- Understand the impact of factors such as contract type, service usage, tenure, and payment method.
- Visualize churn distribution across different demographic and service-related features.
- Gain actionable insights for strategic business decisions.

---

## 📂 Dataset Information

The dataset was provided for academic use and contains 7043 rows and 21 columns. It includes:

- **Demographics**: Gender, Senior Citizen, Dependents, etc.
- **Services**: Internet, Phone, Streaming TV, etc.
- **Account Information**: Tenure, Contract Type, Payment Method, Monthly/Total Charges.
- **Target Variable**: `Churn` (Yes/No)

---

## 🔧 Tools & Technologies Used

- **Python 3**
- **Pandas** - data manipulation
- **NumPy** - numerical operations
- **Matplotlib** & **Seaborn** - data visualization
- **Jupyter Notebook** - code exploration and visualization

---

## 📈 Key Analysis Performed

- Data cleaning and preprocessing:
  - Replaced empty values in `TotalCharges`
  - Converted `TotalCharges` to float
  - Transformed binary columns for readability
- Visualizations:
  - Churn distribution by gender, contract, senior citizen status
  - Pie chart of churn vs non-churn
  - Tenure distribution by churn
  - Stacked bar chart of churn by demographic/service feature
  - Multi-plot dashboard for service features
- Pattern observations and summary statistics

---

## 📊 Visual Highlights

- 📍 **High churn among month-to-month contracts**
- 🧓 **Senior citizens churn slightly more**
- 💳 **Electronic check users show higher churn**
- ⌛ **Longer tenure → lower churn likelihood**
- 🌐 **Fiber optic users more likely to churn than DSL users**

---

## 🚀 How to Run

1. Clone the repository or download the project files.
2. Open the Jupyter Notebook or `.py` script.
3. Make sure the dataset `Customer_churn.csv` is in the same directory.
4. Run the cells to explore and visualize the churn data.

---

## 📚 Folder Structure

