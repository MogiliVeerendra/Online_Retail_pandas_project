# 🛒 Online Retail — ML Data Preparation Pipeline

## 📌 Project Overview

This project focuses on transforming a real-world **Online Retail dataset** into a clean, structured, and ML-ready dataset.

The project was developed as part of my journey toward becoming an **AI/ML Developer**, with a focus on understanding how raw business data is processed before it is given to a Machine Learning model.

Rather than directly applying a Machine Learning algorithm to the raw dataset, I implemented a structured data preparation pipeline covering:

- Data Intake
- Data Understanding
- Data Quality Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Transformation
- Feature Engineering
- Categorical Encoding
- ML Preparation

The final output is a **processed ML-ready dataset** that can be used for Machine Learning modeling.

---

# 🎯 Project Objective

The main objective of this project is to understand and implement the complete workflow required to prepare real-world data for Machine Learning.

### Main goals

- Understand a real-world retail dataset
- Identify data quality problems
- Clean and transform the data
- Explore relationships and distributions
- Create meaningful features
- Handle categorical data
- Separate features (`X`) and target (`y`)
- Prepare training and testing datasets
- Build a reproducible ML data preparation pipeline

---

# 📊 Dataset

### Dataset: Online Retail Dataset

The dataset contains transaction-level information from an online retail business.

### Main columns

| Column | Description |
|---|---|
| `InvoiceNo` | Unique invoice/transaction number |
| `StockCode` | Product identification code |
| `Description` | Product description |
| `Quantity` | Number of products purchased |
| `InvoiceDate` | Date and time of the transaction |
| `UnitPrice` | Price of one product |
| `CustomerID` | Customer identification number |
| `Country` | Customer's country |

---

# 🏗️ Project Pipeline

The complete data preparation workflow implemented in this project is:

```text
Raw Dataset
     │
     ▼
01 Data Intake
     │
     ▼
02 Data Understanding
     │
     ▼
03 Data Quality
     │
     ▼
04 Exploratory Data Analysis
     │
     ▼
05 Data Cleaning
     │
     ▼
06 Data Transformation
     │
     ▼
07 Feature Engineering
     │
     ▼
08 Encoding
     │
     ▼
09 ML Preparation
     │
     ▼
Processed ML-Ready Dataset
     │
     ▼
Future Modeling.