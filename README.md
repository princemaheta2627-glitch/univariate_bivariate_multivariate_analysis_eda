# 🛒 Supermarket Sales EDA | Univariate, Bivariate & Multivariate Analysis

# 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **Supermarket Sales Dataset** from Myanmar. The analysis covers **Univariate**, **Bivariate**, and **Multivariate** techniques to uncover valuable business insights related to branch performance, customer behavior, payment preferences, product sales, and seasonal trends.

The project demonstrates practical data analysis skills using **Python**, **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**.

---

# 🎯 Objectives

- Understand the dataset structure and quality
- Perform data profiling and feature engineering
- Separate categorical and numerical features
- Conduct Univariate, Bivariate, and Multivariate analysis
- Analyze branch performance and customer behavior
- Discover sales patterns across products and time
- Generate meaningful business insights using visualizations

---

# 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | Supermarket Sales |
| Rows | 1,000 |
| Columns | 17 |
| Branches | 3 |
| Cities | Yangon, Mandalay, Naypyitaw |
| Product Lines | 6 |
| Payment Methods | 3 |
| Time Period | January – March 2019 |
| Missing Values | None |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

# 📂 Project Structure

```
Supermarket-Sales-EDA/
│
├── supermarket_sales.csv
├── supermarket_sales_eda.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── branch_distribution.png
│   ├── payment_methods.png
│   ├── rating_distribution.png
│   ├── cogs_distribution.png
│   ├── gross_income_branch.png
│   ├── product_line_analysis.png
│   ├── payment_heatmap.png
│   └── monthly_sales.png
```

---

# 📈 Exploratory Data Analysis

The project includes:

### 🔹 Univariate Analysis
- Branch Distribution
- Payment Method Distribution
- Customer Rating Distribution
- Cost of Goods Sold (COGS)

### 🔹 Bivariate Analysis
- COGS vs Customer Rating
- Gross Income vs Rating
- Branch vs Gross Income
- Gender vs Gross Income
- Product Line vs Gross Income
- Product Line vs Unit Price

### 🔹 Multivariate Analysis
- Payment Method by City
- Product Line vs Quantity Sold
- Branch Performance Comparison
- Customer Type Analysis

### 🔹 Time Series Analysis
- Sales by Day of Week
- Monthly Sales Trend

---

# 📊 Key Visualizations

- 📍 Branch-wise Sales Distribution
- 💳 Payment Method Analysis
- ⭐ Rating Distribution
- 📦 COGS Distribution
- 💰 Gross Income by Branch
- 🛍️ Product Line Performance
- 🔥 Payment Heatmap
- 📅 Weekly Sales Trend
- 📈 Monthly Sales Trend

---

# 🔍 Key Insights

- 🏪 Branch C (Naypyitaw) generates the highest gross income.
- 💳 Ewallet is the most preferred payment method.
- ⭐ Customer ratings follow an approximately normal distribution.
- 📦 COGS is positively skewed with several high-value transactions.
- 🛒 Home & Lifestyle generates the highest gross income.
- 💰 Sports & Travel has the highest average unit price.
- 📱 Electronic Accessories records the highest sales quantity.
- 👥 Loyalty members spend more than non-members.
- 📅 Saturday is the busiest sales day.
- 📈 January records the highest monthly sales.

---

# 🧹 Data Preparation

- Checked missing values
- Verified data types
- Classified categorical and numerical columns
- Feature engineering using Date column
- Created:
  - Day of Week
  - Month

---

# 💡 Business Questions Solved

- Which branch performs best?
- Which payment method is most popular?
- Does spending affect customer ratings?
- Which branch generates the highest profit?
- Which product line earns the most income?
- Which product has the highest unit price?
- Which payment method is preferred in each city?
- Which product line sells the highest quantity?
- Which day generates maximum sales?
- Which month records the highest revenue?

---

# 📚 Python Concepts Used

- Pandas
- NumPy
- Data Cleaning
- Feature Engineering
- GroupBy
- Crosstab
- Heatmaps
- Scatterplots
- Boxplots
- Countplots
- Barplots
- Distribution Plots
- Correlation Analysis

---

# 🚀 Future Improvements

- 📈 Sales Forecasting
- 🤖 Customer Segmentation
- 📊 Interactive Streamlit Dashboard
- 💬 Customer Rating Prediction
- 🛒 Market Basket Analysis
- 📉 Business KPI Dashboard
- 🔮 Machine Learning Models

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/supermarket-sales-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install manually

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📸 Sample Output

Create an **images** folder and include screenshots from your notebook.

```
images/
├── branch_distribution.png
├── payment_methods.png
├── rating_distribution.png
├── gross_income_branch.png
├── payment_heatmap.png
├── monthly_sales.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Scientist | Data Analyst

🔗 GitHub: https://github.com/princemaheta2627-glitch

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is created for educational and portfolio purposes.
