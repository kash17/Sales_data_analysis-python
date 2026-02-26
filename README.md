# Sales_data_analysis-python
Sales Data Analysis using Python (Pandas, NumPy, Matplotlib)

# 📊 Sales Data Analysis using Python

## 📌 Project Overview
This project performs an end-to-end Sales Data Analysis using Python.  
The objective is to clean raw transactional data, perform Exploratory Data Analysis (EDA), and generate actionable business insights to support data-driven decision making.

This project demonstrates practical skills required for a **Data Analyst role** including:
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Data Visualization

---

## 🎯 Business Objectives

- Analyze regional sales performance
- Calculate Revenue and Profit
- Evaluate Profit Margin
- Identify high-performing and underperforming regions
- Provide business recommendations for revenue optimization

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📂 Project Structure

## 📊 Key Metrics Calculated

### 🔹 Revenue


Revenue = Quantity × Unit_Price


### 🔹 Profit

Profit = Revenue − Cost


### 🔹 Profit Margin

Profit_Margin = Profit / Revenue (if Revenue > 0)


Used safe conditional logic to avoid division-by-zero errors:

```python
df['Profit_Margin'] = np.where(
    df['Revenue'] > 0,
    df['Profit'] / df['Revenue'],
    0
)
📈 Exploratory Data Analysis (EDA)

Performed:

Revenue by Region Analysis

Profit Distribution Analysis

Profit Margin Comparison

Regional Performance Comparison using Matplotlib

Identification of revenue concentration trends

💡 Key Insights

North America generated the highest revenue.

Certain regions show strong sales but lower margins.

Cost optimization opportunities exist in mid-performing regions.

Profit margin variability indicates pricing and cost control impact.

🚀 How to Run This Project
1️⃣ Clone Repository
git clone https://github.com/kash17/Sales_data_analysis-python.git
cd Sales_data_analysis-python

Install Dependencies
pip install -r requirements.txt
3️⃣ Run Notebook
jupyter notebook

Open:

notebooks/sales data analysis.ipynb

Future Improvements

Add interactive dashboard (Streamlit / Power BI)

Author

Karishma Thakare
Aspiring Data Analyst
GitHub: https://github.com/kash17
