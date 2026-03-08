# Chips Sales & Store Trial Analysis

This project analyzes customer purchasing behaviour and evaluates the impact of a retail store trial conducted in selected supermarkets.

The analysis is divided into two main parts:

1. Customer & Sales Analysis
2. Store Trial Impact Analysis

The goal is to understand customer segments and determine whether a store trial successfully increased chip sales.

---

# Project Objectives

The project aims to answer two main business questions:

### Task 1
Understand customer purchasing behaviour and identify the customer segments that contribute most to chip sales.

### Task 2
Evaluate the effectiveness of a store trial conducted in selected stores by comparing their performance against similar control stores.

---

# Dataset

Two datasets were used in this project:

### Transaction Data
Contains detailed chip purchase transactions including:
- Store number
- Transaction date
- Product name
- Quantity purchased
- Total sales

### Customer Data
Contains customer segmentation information including:
- Life stage
- Premium or budget customer segment

These datasets were merged to analyze both **sales behaviour and customer demographics**.

---

# Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

Main techniques used:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Correlation Analysis
- Magnitude Distance
- Retail Experiment Analysis

---

# Task 1: Customer & Sales Analysis

In the first part of the project, we explored customer behaviour to understand which segments contribute most to chip sales.

## Key Findings

### 1. Major contributing customer groups
The highest total sales came from:

- Older Singles/Couples
- Retirees
- Older Families

These segments represent a large portion of total chip purchases.

---

### 2. Families purchase larger quantities

Families (both young and older) tend to buy **larger quantities per transaction**.

This suggests that households with children are key drivers of chip volume sales.

---

### 3. Young singles tend to pay higher prices

Young Singles/Couples appear to purchase more premium chip products compared to other segments.

This indicates potential opportunities for premium product marketing.

---

# Task 2: Store Trial Impact Analysis

A store trial was conducted in the following locations:

- Store 77
- Store 86
- Store 88

The objective was to determine whether the trial increased chip sales.

To measure the impact fairly, each trial store was compared with a **similar control store**.

---

# Methodology

The analysis followed these steps:

### 1. Create monthly store metrics
Metrics calculated per store:

- Total Sales
- Number of Customers
- Number of Transactions
- Quantity of products sold

---

### 2. Identify similar control stores

Control stores were selected based on similarity during the **pre-trial period**.

Similarity was measured using:

- Pearson Correlation
- Magnitude Distance

Metrics considered:

- Sales
- Customers
- Transactions
- Quantity

Selected control stores:

| Trial Store | Control Store |
|-------------|--------------|
| 77 | 233 |
| 86 | 155 |
| 88 | 237 |

---

### 3. Estimate expected sales

A **scaling factor** was calculated to estimate the expected performance of each trial store based on its control store.

---

### 4. Compare actual vs expected sales

Actual sales were compared with expected sales during the trial period to calculate **incremental impact**.

---

# Trial Results

| Trial Store | Control Store | Incremental Sales |
|-------------|--------------|------------------|
| 77 | 233 | +175 |
| 86 | 155 | +143 |
| 88 | 237 | +500 |

All three trial stores recorded higher actual sales compared to expected sales during the trial period.

---

# Business Insights

The trial appears to have had a **positive impact on chip sales** across all participating stores.

The strongest uplift occurred in **Store 88**, indicating a particularly successful response to the trial strategy.

---

# Recommendations

Based on the analysis:

1. The trial strategy should be considered for rollout across additional stores.

2. Further analysis could identify which specific factors (product placement, promotion, or store layout) drove the increase.

3. Future trials should continue using control store comparison to accurately measure impact.

---

# Key Skills Demonstrated

- Data Cleaning & Preparation
- Customer Segmentation Analysis
- Retail Experiment Evaluation
- Control Store Selection
- Data Visualization
- Business Insight Generation

---


---

# Author

Khaled

Aspiring Data Analyst with interest in business analytics, retail data analysis, and experimentation.
