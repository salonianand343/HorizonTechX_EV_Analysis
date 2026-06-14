# EV_Analysis
# 🚗 Electric Vehicle (EV) Market Analysis

## 📌 Project Overview

The Electric Vehicle (EV) Market Analysis project is an end-to-end Data Analytics project designed to analyze the rapidly growing electric vehicle industry. The project focuses on understanding market trends, vehicle performance, customer preferences, pricing strategies, and sales performance through data-driven analysis.

Using Python for Data Cleaning, Exploratory Data Analysis (EDA), Statistical Analysis, and Machine Learning, and Power BI for interactive dashboard creation, this project provides valuable business insights that can help manufacturers, investors, and decision-makers understand the EV market landscape.

---

## 🎯 Project Objectives

The primary objectives of this project are:

- Clean and preprocess the raw EV dataset.
- Explore sales trends and market performance.
- Analyze the relationship between battery capacity, range, price, and customer ratings.
- Identify top-performing EV brands and market segments.
- Perform statistical analysis to uncover hidden patterns.
- Build a machine learning model to predict annual EV sales.
- Create an interactive Power BI dashboard for business insights and decision-making.

---

## 📊 Dataset Information

The dataset contains detailed information about Electric Vehicles including:

| Feature | Description |
|----------|-------------|
| Brand | EV Manufacturer |
| Model | Vehicle Model |
| Price (USD) | Vehicle Price |
| Battery Capacity (kWh) | Battery Size |
| Range (Miles) | Driving Range |
| Charging Speed | Charging Performance |
| Horsepower | Vehicle Power |
| Customer Rating | User Satisfaction Score |
| Annual Sales Units | Total Units Sold |
| Country of Origin | Manufacturing Country |
| Market Segment | Budget, Mid-range, Luxury, etc. |

---

# 🛠️ Technologies Used

## Programming Languages
- Python

## Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Business Intelligence Tool
- Power BI

## Development Environment
- Jupyter Notebook
- VS Code

---

# 🔍 Project Workflow

## 1. Data Collection

The EV dataset was imported and loaded using Pandas for further analysis.

```python
import pandas as pd

df = pd.read_csv("ev_market_2026.csv")
```

---

## 2. Data Cleaning

Data cleaning was performed to improve data quality and reliability.

### Tasks Performed

- Removed duplicate records
- Handled missing values
- Corrected data types
- Renamed columns
- Standardized dataset structure

## 3. Exploratory Data Analysis (EDA)

EDA was conducted to discover patterns, trends, and relationships within the dataset.

### Analysis Performed

### 📈 Sales Analysis
- Top-selling EV brands
- Sales distribution across countries
- Market segment performance

### 🔋 Battery Performance Analysis
- Battery Capacity vs Driving Range
- Charging Speed comparison

### 💰 Pricing Analysis
- Price distribution
- Price vs Customer Rating

### ⭐ Customer Analysis
- Customer rating trends
- Brand-wise customer satisfaction

---

## Key Visualizations

### Sales by Brand
Identifies the most successful EV manufacturers.

### Country-wise Sales
Shows the contribution of each country to EV sales.

### Market Segment Distribution
Highlights market share among various vehicle segments.

### Battery Capacity vs Range
Analyzes the relationship between battery size and driving range.

### Price vs Customer Rating
Examines whether expensive vehicles receive better customer ratings.

### Correlation Heatmap
Displays relationships among numerical variables.

---

# 📊 Statistical Analysis

Statistical techniques were applied to understand the dataset more deeply.

### Measures Used

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Correlation Analysis
- Distribution Analysis

### Correlation Analysis

A heatmap was created to identify relationships among:

- Price
- Battery Capacity
- Range
- Horsepower
- Customer Rating
- Annual Sales

---

# 🤖 Machine Learning Model

## Objective

Predict the annual sales units of electric vehicles using historical vehicle specifications and market data.

### Model Used

- Random Forest Regressor

### Machine Learning Workflow

1. Data Preprocessing
2. Feature Encoding
3. Train-Test Split
4. Model Training
5. Prediction
6. Model Evaluation

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📈 Power BI Dashboard

An interactive 3-page Power BI dashboard was developed to present insights effectively.

---

## Dashboard Page 1: Executive Overview

### KPIs

- Total Sales Units
- Average Price
- Average Battery Capacity
- Average Driving Range
- Average Customer Rating

### Visualizations

- Sales by Brand
- Country-wise Sales Map
- Market Segment Distribution
- Sales Trend Analysis

---

## Dashboard Page 2: Sales & Market Analysis

### Visualizations

- Top Selling Brands
- Country Performance
- Market Segment Analysis
- Sales Comparison

### Insights

- Best-performing brands
- Leading markets
- Popular vehicle segments

---

## Dashboard Page 3: Performance & Customer Insights

### Visualizations

- Battery Capacity vs Range
- Price vs Customer Rating
- Charging Speed Analysis
- Customer Rating Distribution

### Insights

- Factors influencing customer satisfaction
- Performance comparison among EV brands

---

# 💡 Key Business Insights

### 1. Market Leaders

Certain EV brands dominate annual sales due to strong brand reputation and market presence.

### 2. Battery Impact

Higher battery capacity generally results in increased driving range.

### 3. Customer Satisfaction

Vehicles with better charging speeds and performance tend to receive higher customer ratings.

### 4. Market Segmentation

Mid-range EVs contribute a significant share of total market sales due to affordability.

### 5. Pricing Trends

Higher prices do not always guarantee higher customer ratings or sales performance.

### 6. Regional Performance

Some countries contribute significantly more to EV sales than others, highlighting regional market opportunities.

---

# 📁 Project Structure

```text
EV-Market-Analysis/
│
├── Dataset/
│   └── ev_market_2026.csv
│
├── Notebooks/
│   └── EV_EDA_Analysis.ipynb
│
├── PowerBI/
│   └── EV_Market_Dashboard.pbix
│
├── Images/
│   ├── Dashboard_Page1.png
│   ├── Dashboard_Page2.png
│   └── Dashboard_Page3.png
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 Future Enhancements

- Real-time EV market monitoring
- Advanced forecasting models
- Customer segmentation analysis
- EV recommendation system
- Streamlit web application
- Integration with live market APIs

---

# 📌 Conclusion

This project demonstrates the complete Data Analytics lifecycle, from data cleaning and exploratory analysis to machine learning and dashboard development. The insights generated help understand EV market dynamics, customer behavior, and sales performance, making it a valuable project for Data Analyst and Data Science portfolios.

---

# 👨‍💻 Author

**Saloni Anand**

Data Analytics | Python | Power BI 

---
