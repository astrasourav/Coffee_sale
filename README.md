# ☕ Coffee Sales Data Analysis Project

### 📊 Project Overview
This project aims to perform a detailed analysis of coffee sales data. The primary objective is to explore sales patterns, analyze payment methods, and analyze popular coffee types. By cleaning and visualizing the dataset, valuable insights can be derived to inform business decisions.

---

## 📁 Dataset
The dataset contains the following key columns:
- **`datetime`**: The date and time of the transaction.
- **`coffee_name`**: The name/type of coffee sold.
- **`cash_type`**: The method of payment used (e.g., `cash`, `card`).
- **`money`**: The amount of money earned in the transaction.

---

## 🔑 Key Features of the Analysis

### 1. Data Cleaning
- Checked for missing values in the dataset.
- Identified and removed duplicate entries.
- Ensured consistency in `cash_type` values (e.g., correcting payment method labels).

### 2. Payment Data Analysis
- Analyzed the distribution of payment methods (`cash`, `card`, etc.).
- Visualized the payment method distribution using:
  - **Bar Chart**: For comparison of payment methods.
  - **Pie Chart**: For relative proportions of each payment type.

### 3. Popular Coffee Types
- Counted the frequency of each coffee type sold.
- Visualized the top-selling coffee types using a bar chart.

### 4. Total Sales Per Day
- Grouped the sales by date to calculate the **Total Sales** per day.
- Visualized the daily sales using a bar chart.

---

## 📊 Visualizations
The following visualizations were created:
- **Payment Distribution**:
  - Bar Chart: To show the count of different payment methods.
  - Pie Chart: To show the proportion of each payment method.
- **Daily Sales**:
  - Bar Chart: To show total sales for each day.
- **Popular Coffee Types**:
  - Bar Chart: To show the count of different coffee types.
  - - Pie Chart: To show the proportion of each coffee types.

---

## 🛠️ Libraries Used
- **pandas**: For data cleaning, manipulation, and analysis.
- **matplotlib**: For creating visualizations like bar charts, pie charts, and line plots.

---

## 🚀 How to Run the Project
To run the analysis and visualizations, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coffee-sales-analysis.git
