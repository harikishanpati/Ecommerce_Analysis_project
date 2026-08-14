# 🛒 E-Commerce Sales & Profit Analysis

An exploratory data analysis (EDA) project using the **Sample Superstore dataset** to analyze sales, profit, product categories, sub-categories, and monthly business performance through Python and interactive visualizations.

## 📌 Project Overview

This project analyzes an e-commerce retail dataset to understand business performance and identify patterns in:

* 📈 Monthly sales
* 💰 Monthly profit
* 🗂️ Sales by category
* 📦 Sales by sub-category
* 💵 Profit by category
* 📊 Overall sales and profit trends

The analysis is performed using **Python, Pandas, and Plotly** to transform raw transactional data into meaningful business insights.

## 🎯 Objectives

The main objectives of this project are to:

1. Load and explore the Superstore e-commerce dataset.
2. Perform basic data inspection and statistical analysis.
3. Convert date columns into appropriate datetime formats.
4. Extract useful time-based features from order dates.
5. Analyze monthly sales performance.
6. Compare sales across different product categories and sub-categories.
7. Analyze monthly profit trends.
8. Compare profitability across product categories.
9. Present findings using interactive Plotly visualizations.

## 🗃️ Dataset

The project uses the **Sample Superstore** dataset.

The dataset contains transactional information related to retail orders, including fields such as:

* Order Date
* Ship Date
* Category
* Sub-Category
* Sales
* Profit
* And other order/customer/product attributes

> **Note:** The dataset file (`Sample - Superstore.csv`) is required to run the notebook.

## 🛠️ Technologies Used

| Technology           | Purpose                           |
| -------------------- | --------------------------------- |
| Python               | Data analysis                     |
| Pandas               | Data manipulation and aggregation |
| Plotly Express       | Interactive visualizations        |
| Plotly Graph Objects | Visualization support             |
| Jupyter Notebook     | Development environment           |

## 🔍 Analysis Performed

### 1. Data Loading & Exploration

The dataset is imported using Pandas and initially explored using:

* `head()`
* `describe()`
* `info()`

This provides an overview of the dataset structure, numerical statistics, and data types.

### 2. Data Preprocessing

The `Order Date` and `Ship Date` columns are converted into datetime format.

Additional time-based features are created:

* **Order Month**
* **Order Year**
* **Order Day of Week**

These features enable time-based business analysis.

### 3. Monthly Sales Analysis

Total sales are aggregated by month to identify variations in sales performance throughout the year.

A Plotly line chart is used to visualize the monthly sales trend.

### 4. Category-Wise Sales Analysis

Sales are grouped according to product category.

The project visualizes the contribution of different categories using a Plotly pie chart.

### 5. Sub-Category Sales Analysis

Sales are aggregated across individual product sub-categories.

A bar chart is used to compare sales performance between sub-categories.

### 6. Monthly Profit Analysis

Total profit is calculated for each month.

A bar chart is used to visualize monthly profitability.

### 7. Category-Wise Profit Analysis

Profit is grouped by product category to understand which major categories contribute most to overall profitability.

## 📊 Visualizations

The notebook generates several interactive visualizations, including:

* 📈 Monthly Sales Line Chart
* 🥧 Sales by Category Pie Chart
* 📊 Sales by Sub-Category Bar Chart
* 📊 Monthly Profit Bar Chart
* 🥧 Profit by Category Pie Chart

Plotly allows these visualizations to be interactively explored.

## 📁 Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── ecommerce_project.ipynb
├── Sample - Superstore.csv
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/E-Commerce-Sales-Analysis.git
cd E-Commerce-Sales-Analysis
```

### 2. Install the required libraries

```bash
pip install pandas plotly jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open:

```text
ecommerce_project.ipynb
```

Make sure `Sample - Superstore.csv` is located in the appropriate working directory.

### 5. Run the cells

Execute the notebook cells sequentially to reproduce the data analysis and visualizations.

## 💡 Key Takeaways

The project demonstrates how raw retail transaction data can be transformed into useful business information through:

**Data Loading → Data Cleaning → Feature Extraction → Aggregation → Visualization → Business Analysis**

It provides a foundation for understanding sales and profitability patterns in an e-commerce/retail environment.

## 🔮 Future Improvements

The project can be extended by adding:

* Customer segmentation
* Regional sales analysis
* Customer-level profitability
* Discount vs. profit analysis
* Shipping-mode analysis
* Year-over-year growth analysis
* Sales forecasting
* Profit prediction using machine learning
* An interactive Power BI/Tableau dashboard
* KPI dashboard with Sales, Profit, Orders, and Profit Margin

## 👨‍💻 Author

**Harikishan Pati**

B.Tech 
National Institute of Technology, Rourkela

---

⭐ If you found this project useful, consider giving the repository a star!
