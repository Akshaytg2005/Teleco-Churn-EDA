# Telecom Customer Churn Analysis

## Project Overview
Customer churn is a critical challenge for telecom companies because acquiring new customers is often more expensive than retaining existing ones.  

This project performs an **Exploratory Data Analysis (EDA)** on a telecom customer dataset to identify key factors associated with customer churn. The goal is to uncover patterns in customer behavior that may help telecom providers improve retention strategies.

---

## Dataset
The dataset used in this project is the **Telco Customer Churn Dataset** containing information about customer demographics, services subscribed, billing details, and churn status.

**Dataset size**
- Customers: 7,043
- Features: 21

**Target variable**
- `Churn` – Indicates whether a customer left the service.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Project Workflow

### 1. Data Overview
Initial exploration of dataset structure including:
- Dataset dimensions
- Column types
- Summary statistics
- Churn distribution

### 2. Data Cleaning
Data preprocessing steps included:
- Converting `TotalCharges` to numeric format
- Handling missing values
- Verifying categorical variables
- Checking for duplicate records

### 3. Customer Profiling
Exploratory analysis of key variables:
- Customer tenure distribution
- Monthly charges distribution
- Contract type distribution
- Internet service distribution

### 4. Churn Analysis
Relationships between churn and important features were analyzed, including:

- Contract type vs churn
- Tenure vs churn
- Monthly charges vs churn
- Internet service type vs churn

---

## Key Findings

### 1. Contract Type Strongly Influences Churn
Customers on **month-to-month contracts have a churn rate of ~43%**, significantly higher than those on one-year (~11%) and two-year (~3%) contracts.

### 2. Early Lifecycle Churn
Customers with **low tenure are much more likely to churn**, indicating the early months are the highest risk period.

### 3. Higher Monthly Charges Linked to Churn
Customers paying **higher monthly charges tend to churn more frequently**, suggesting potential price sensitivity.

### 4. Fiber Optic Customers Show Highest Churn
Fiber optic users have a **churn rate of ~42%**, which is significantly higher than DSL (~19%) and customers without internet (~7%).

---

## Business Recommendations

Based on the analysis, telecom providers may consider:

- Encouraging customers to switch to **long-term contracts**
- Improving **customer onboarding and early retention strategies**
- Reviewing **pricing and value of premium service tiers**
- Investigating **service quality for fiber optic customers**

---

## Project Structure
Telecom-Churn-EDA
│
├── telecom_churn_analysis.ipynb
├── README.md
└── dataset.csv

---

## Future Improvements
Possible extensions for this project include:

- Building a **machine learning model to predict churn**
- Feature engineering for better churn prediction
- Customer segmentation analysis
- Survival analysis to estimate churn timing

---

## Author
Akshay T Geevarghese  
B.Tech Electrical and Computer Student
TKMCE
Aspiring Data Analyst / Data Scientist
