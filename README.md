# Demand Forecasting & Forecast Analysis

## 📌 Project Overview

This project focuses on forecasting daily product demand across multiple stores and SKUs using historical sales data.

The objective was to build a machine learning-based demand forecasting system that can:

- Analyze historical sales patterns
- Identify demand trends and seasonality
- Engineer time-series and promotional features
- Forecast future daily demand
- Evaluate forecast accuracy
- Quantify forecast uncertainty
- Identify Store × SKU combinations with higher demand and forecast uncertainty
- Present the results through an interactive Power BI dashboard

---

## 🎯 Business Problem

Accurate demand forecasting is important for businesses operating across multiple stores and products.

Poor forecasts can lead to:

- Excess inventory
- Stockouts
- Inefficient replenishment planning
- Poor allocation of products across stores

This project focuses on the forecasting side of the problem by estimating future demand and understanding the uncertainty associated with those predictions.

---

## 📊 Dataset

The dataset contains approximately **1.1 million daily observations** covering:

- **3 years** of data
- **1,004 complete Store × SKU combinations**
- **13 stores**
- **7 countries**
- **9 cities**
- **60 suppliers**
- **5 product categories**
- **15 subcategories**
- **6 brands**
- **4 sales channels**

### Key Variables

| Category | Variables |
|---|---|
| Time | Date, Year, Month, Week, Weekday, Weekend |
| Demand | Units Sold |
| Pricing | List Price, Discount %, Gross Sales, Net Sales |
| Promotion | Promo Flag, Holiday Flag |
| Weather | Temperature, Rainfall |
| Product | SKU, Category, Subcategory, Brand |
| Store | Store ID, Country, City, Channel |
| Supply | Lead Time, Supplier ID |
| Inventory | Stock on Hand, Stockout Flag |

---

## 🔍 Project Workflow

```text
Raw Data
    ↓
Data Validation
    ↓
Exploratory Data Analysis
    ↓
Feature Engineering
    ↓
Baseline Forecasting
    ↓
Random Forest Forecasting
    ↓
Model Evaluation
    ↓
Forecast Error Analysis
    ↓
Demand Uncertainty
    ↓
Store × SKU Prioritization
    ↓
Power BI Dashboard
