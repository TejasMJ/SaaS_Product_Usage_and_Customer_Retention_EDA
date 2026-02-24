# SaaS Product Usage & Customer Retention EDA 📊
---
A comprehensive Exploratory Data Analysis (EDA) of a SaaS customer dataset focused on understanding product usage behavior, customer engagement, revenue patterns, and churn dynamics.
The project leverages Python-based analytics and visualization to uncover actionable insights that support retention, growth, and customer lifecycle optimization.


## 🌟 Features

### Core Features
- Data Cleaning & Preprocessing: Data type standardization, handling missing and invalid values, and business-aware imputation strategies.
- Customer Segmentation Analysis: Distribution across user demographics, signup channels, and shopping frequency segments.
- Shopping Behavior & Engagement Analysis: Browsing patterns, product views, add-to-cart activity, and purchase frequency insights.
- Conversion Funnel Analysis: Drop-off analysis across browsing, cart, and checkout stages to identify missed conversions.
- Pricing & Abandonment Insights: Price sensitivity, comparison behavior, and key drivers of cart abandonment.
- Recommendations & Personalization Analysis: Effectiveness of product recommendations in influencing purchase decisions.
- Customer Support & Satisfaction Analysis: Impact of complaints, service quality, CSAT, and NPS on trust and loyalty.
- Review & Post-Purchase Behavior: Influence of reviews, ratings, and post-purchase experience on future purchase intent.
- Growth Opportunity Identification: Occasional vs frequent shopper analysis to identify scalable growth levers.
- Visualization: Insight-driven static and interactive visualizations using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
SaaS_Customer_Retention_EDA/
├── saas_customer_data.csv              # SaaS customer-level dataset
├── SaaS_Customer_Retention_EDA.ipynb   # Jupyter Notebook with full EDA
├── requirements.txt                    # Python dependencies
└── venv/                               # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+----------------------------+
|        DATA LAYER          |
|  Customer-level SaaS data  |
|      (CSV format)          |
+-------------+--------------+
              ↓
+-------------------------------+
|        ANALYSIS LAYER         |
|  - Data Cleaning & Validation |
|  - Usage & Engagement         |
|  - Revenue & Billing          |
|  - Support & Satisfaction     |
|  - Churn & Retention          |
+-------------+-----------------+
              ↓
+-----------------------------------------+
|         VISUALIZATION LAYER              |
|  - Distribution & Trend Analysis         |
|  - Retention & Churn Comparisons         |
|  - Segment-level Insights                |
|  - Interactive & Static Visuals          |
+-----------------------------------------+

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle](https://www.kaggle.com/datasets/miadul/customer-churn-prediction-business-dataset)

---

## 📊 Dataset Overview

Granularity: Customer-level data

Key Feature Groups:
- **Demographics & Segmentation:** Age group, gender, and shopping frequency segments  
- **Shopping & Browsing Behavior:** Purchase categories, product search methods, and search result exploration  
- **Cart & Checkout Behavior:** Add-to-cart activity, browsing vs buying patterns, and cart abandonment factors  
- **Pricing & Decision Drivers:** Price sensitivity, cross-platform comparison behavior, and deal influence  
- **Reviews & Trust Signals:** Importance of customer reviews, review participation, and rating accuracy perception  
- **Personalization & Recommendations:** Frequency of personalized recommendations and purchases influenced by them  
- **Post-Purchase Experience & Satisfaction:** Shopping satisfaction, service appreciation, and improvement areas  
- **Feedback & Advocacy Signals:** Reviews left, platform ratings, and qualitative feedback  

Target Variable:
- **Purchase Completion / Shopping Satisfaction** (behavioral outcome analysis)

Context:
E-commerce platforms generate rich behavioral and feedback-driven data, but translating browsing behavior, pricing perception, reviews, and service quality into actual purchases and long-term trust remains challenging. This dataset enables a holistic exploration of how discovery, conversion friction, personalization, and post-purchase experience shape consumer behavior and satisfaction.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/SaaS_Product_Usage_and_Customer_Retention_EDA.git
cd Google-Play-Store-App-EDA-
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 SaaS Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Standardized data types across categorical and numerical features
- Handled missing values using business-aware imputation strategies
- Cleaned invalid entries while preserving meaningful signals
- Retained legitimate outliers to reflect real-world user behavior

### Exploratory Analysis
- Customer segment distribution and shopping frequency patterns
- Browsing, cart interaction, and feature adoption behavior
- Tenure-based purchasing and satisfaction trends
- Revenue concentration across high- and low-value customers

### Retention & Behavior Insights
- Identification of early-stage drop-off risk in the shopping journey
- Impact of engagement depth on repeat purchases and loyalty
- Role of pricing perception, cart friction, and service experience on abandonment
- Customer satisfaction signals as leading indicators of future behavior

### Visualization
- Interactive, insight-driven charts using **Plotly**
- Static analytical plots using **Seaborn** and **Matplotlib**
- Business-focused visual storytelling to highlight key decision drivers

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
