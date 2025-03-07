# Walmart Sales Analysis

## Table of Contents
- [Introduction](#introduction)
- [Project Workflow](#project-workflow)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Insights](#key-insights)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Future Enhancements](#future-enhancements)

---

## Introduction

This project analyzes Walmart's sales data to identify trends, seasonality, and performance insights. Using Python for data cleaning, MySQL for data processing, and Power BI for visualization, the project aims to provide actionable insights into sales patterns.

---

## Project Workflow

1. **Data Cleaning (Python)**
   - The raw dataset (`Walmart_Data.xls`) was cleaned using `pandas`.
   - The processed data was stored as `Cleaned_walmart_data.xls`.

2. **Data Analysis (MySQL)**
   - Data was imported into MySQL for structured queries.
   - SQL queries (`SQL Queries.sql`) were used for aggregation and segmentation.

3. **Visualization (Power BI)**
   - Interactive dashboards were created using `Walmart_Analysis.pbix`.
   - PNG files (`Dashboard1.png` and `Dashboard2.png`) show static representations.

---

## Technologies Used

- **Python**: Data processing (`pandas`)
- **MySQL**: Querying and filtering sales data
- **Power BI**: Creating interactive dashboards
- **Jupyter Notebook**: Analysis documentation (`Python file.ipynb`)

---

## Project Structure

```
├── Dashboard1.png           # First dashboard (Power BI)
├── Dashboard2.png           # Second dashboard (Power BI)
├── Walmart_Analysis.pbix    # Power BI dashboard file
├── icon1.jpeg               # Supporting images
├── icon2.jpeg
├── icon3.jpg
├── icon4.jpeg
├── Python file.ipynb        # Jupyter Notebook for data cleaning
├── SQL Queries.sql          # SQL queries for analysis
├── requirements.txt         # Dependencies
├── Walmart_Data.xls         # Raw sales dataset
├── Cleaned_walmart_data.xls # Cleaned dataset
├── walmart-10k-sales-datasets.zip # Original dataset archive
```

---

## Key Insights

### **Dashboard 1**
- **Peak Sales**: December sees the highest sales due to holiday demand.
- **Top-Selling Categories**: Fashion and Home & Lifestyle dominate revenue.
- **Regional Trends**: North America and Europe lead in sales performance.

### **Dashboard 2**
- **Seasonality**: Sales dip in January and mid-year.
- **Forecasting**: Revenue trends show growth from 2023 onwards.
- **Customer Ratings**: Average satisfaction score is 5.83/10.

---

## Getting Started

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-repo-url
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook**
   - Open `Python file.ipynb` and execute all cells.
4. **MySQL Setup**
   - Import `Cleaned_walmart_data.xls` into MySQL.
   - Run SQL queries from `SQL Queries.sql`.
5. **Power BI Dashboard**
   - Open `Walmart_Analysis.pbix` in Power BI.
   - Alternatively, view `Dashboard1.png` and `Dashboard2.png`.

---

## Dataset

The dataset is sourced from Kaggle:
[Walmart 10K Sales Dataset](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)

Download the dataset using Kaggle API or manually place it in the project folder.

---

## Future Enhancements

- **Improved Dashboards**: Add drill-down filters for deeper insights.
- **Machine Learning Forecasting**: Implement predictive models.
- **Automation**: Create scripts for end-to-end data processing.

---

## Acknowledgments

- **Dataset**: [Kaggle](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)
- **Tools Used**: Python, MySQL, Power BI
