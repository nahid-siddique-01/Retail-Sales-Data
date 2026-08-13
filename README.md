# 📊 Retail Sales Data Analysis & EDA

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a retail sales dataset using Python. The analysis focuses on understanding sales trends, customer demographics, product-category performance, and relationships between numerical variables.

The project was created using **Jupyter Notebook** and can also be run in **VS Code**.

## 🎯 Objectives

* Inspect and understand the retail sales dataset
* Clean and preprocess the data
* Calculate statistical measures such as mean, median, mode, and standard deviation
* Analyze monthly and quarterly sales trends
* Study customer age-group distribution
* Analyze revenue by gender
* Compare revenue across product categories
* Identify relationships between numerical variables using correlation analysis
* Visualize transaction amounts across product categories
* Avoid misleading analysis where the dataset does not contain the required information

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook / VS Code**

## 📂 Project Structure

```text
Retail-Sales-EDA/
│
├── retail/
│   └── retail_sales_dataset.csv
│
├── Retail_Sales_EDA.ipynb
│
└── README.md
```

## 🔍 Analysis Performed

### 1. Dataset Inspection

The dataset is inspected to understand its shape, columns, data types, and missing values.

### 2. Data Cleaning

The project:

* Converts the `Date` column into a proper datetime format
* Converts numerical columns into numeric data types
* Removes duplicate records
* Handles missing numerical values

### 3. Statistical Analysis

The following statistical measures are calculated for numerical variables:

* Mean
* Median
* Mode
* Standard deviation
* Descriptive statistics

### 4. Monthly Sales Trend

Monthly sales are calculated using `Total_Amount`.

**Key observation:** The highest monthly sales occur in **2023-05**, while the lowest occur in **2024-01**.

### 5. Quarterly Sales Trend

Sales are grouped by quarter to understand larger business trends.

**Key observation:** **2023 Q4** has the strongest sales, while **2024 Q1** has the weakest.

### 6. Customer Age-Group Distribution

Customers are divided into different age groups to understand the distribution of transactions.

**Key observation:** The **46–55** age group has the largest number of transactions.

### 7. Gender Analysis

Revenue is grouped by gender to compare total revenue contribution.

**Key observation:** **Female customers contribute the highest total revenue** in this dataset.

> This is a descriptive finding and does not imply that gender causes higher spending.

### 8. Product Category Analysis

Revenue is analyzed across different product categories.

**Key observation:** **Electronics** generates the highest revenue among the available product categories.

### 9. Top 10 Products

A genuine Top-10 individual product ranking was not performed because the supplied dataset contains `Product_Category` but does not contain individual product/item names.

The project therefore avoids creating or assuming product names that are not present in the dataset.

### 10. Correlation Analysis

A correlation heatmap is created for:

* Age
* Quantity
* Price per Unit
* Total Amount

The heatmap helps identify linear relationships between numerical variables.

> Correlation represents association, not causation.

### 11. Additional Visualization

A box plot is used to analyze the distribution of transaction amounts across product categories.

## 📈 Key Insights

* **Electronics** is the highest-revenue product category.
* **Female** customers contribute the highest total revenue.
* The **46–55** age group represents the largest number of transactions.
* **2023 Q4** is the strongest quarter in terms of sales.
* **2024 Q1** is the weakest quarter.
* Monthly sales analysis can help with inventory and promotional planning.
* Correlation analysis provides insights into relationships among numerical variables.

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd Retail-Sales-EDA
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the Notebook

Using Jupyter:

```bash
jupyter notebook
```

Or open the `.ipynb` file directly in **VS Code** with the Jupyter extension installed.

### 4. Run All Cells

Make sure the dataset is located at:

```text
retail/retail_sales_dataset.csv
```

Then run the notebook cells from top to bottom.

## 💡 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization
* Pandas DataFrame Operations
* GroupBy Analysis
* Time-Series Aggregation
* Correlation Analysis
* Business Insight Generation
