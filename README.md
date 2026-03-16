# Quantium Retail Analytics – Data Analytics Virtual Experience

This project was completed as part of the **Quantium Data Analytics Virtual Experience Program on Forage**.  
The objective of this project was to analyze retail transaction data to generate **business insights on customer behavior, product preferences, and store trial performance**.

The analysis focuses on identifying key customer segments, understanding purchasing patterns, and evaluating the effectiveness of store trials using a data-driven approach.

---

# Project Objectives

The main goals of this project were:

- Clean and prepare raw retail transaction data
- Engineer useful features from product information
- Identify high-value customer segments
- Analyze brand and pack size preferences
- Evaluate the impact of trial stores using control stores
- Generate actionable business insights using data visualization

---

# Dataset

The project uses two datasets:

**1. Transaction Data**
- Transaction ID
- Product name
- Quantity purchased
- Total sales
- Transaction date
- Store number
- Loyalty card number

**2. Customer Purchase Behaviour Data**
- Loyalty card number
- Customer lifestage
- Premium customer category

These datasets were merged to perform **customer segmentation and retail performance analysis**.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Workflow

## 1. Data Cleaning

Key preprocessing steps included:

- Converting Excel date format to calendar date
- Removing irrelevant products (e.g., salsa items)
- Detecting and removing extreme outliers in purchase quantity
- Standardizing brand names
- Extracting useful product attributes

Example features engineered:

- **PACK_SIZE** extracted from product name
- **BRAND** extracted and standardized

---

## 2. Feature Engineering

Additional variables were created to support deeper analysis:

- Product pack size
- Product brand
- Monthly store metrics
- Average transactions per customer

These features enabled **customer behavior analysis and store comparison**.

---

# Customer Segment Analysis

Customer segments were analyzed based on:

- **Lifestage**
- **Premium customer category**

Total sales were aggregated by segment to identify the most valuable customer groups.

### Key Insight

The **Young Singles/Couples – Mainstream** segment generated the highest sales and became the focus for deeper analysis.

---

# Brand Affinity Analysis

To understand purchasing behavior, the project compared:

- Brand preferences of the target segment
- Brand preferences of the rest of the population

Brands with the highest affinity for the target segment included:

- Tyrrells
- Twisties
- Doritos
- Tostitos
- Kettle

These brands were **significantly more likely to be purchased by Young Singles/Couples (Mainstream)**.

---

# Pack Size Preference Analysis

The analysis also examined which product sizes the target segment preferred.

Top pack sizes included:

- 270g
- 380g
- 330g
- 134g
- 210g

This insight can help retailers **optimize product placement and inventory decisions**.

---

# Store Trial Analysis

A store trial experiment was evaluated to determine if a new store layout or marketing strategy improved sales.

### Steps performed:

1. Calculated monthly metrics for each store:
   - Total sales
   - Number of customers
   - Number of transactions

2. Created **control stores** using similarity analysis:
   - Pearson correlation on sales trends
   - Customer count comparison

3. Matched each trial store with the most similar control store.

### Trial-Control Pairs

| Trial Store | Control Store |
|--------------|--------------|
| 77 | 233 |
| 86 | 155 |
| 88 | 178 |

---

# Visualization and Impact Assessment

Time series plots were created to compare:

- Total sales
- Customer counts

between trial stores and their matched control stores.

The trial period (Feb 2019 – Apr 2019) was highlighted to visually assess **whether the trial intervention improved store performance**.

---

# Key Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Customer Segmentation
- Retail Analytics
- Time Series Analysis
- Data Visualization
- Business Insight Generation

---

## Project Structure

```
Quantium-Data-Analytics-Virtual-Experience
│
├── data
│   ├── QVI_transaction_data.xlsx
│   └── QVI_purchase_behaviour.csv
│
├── notebooks
│   └── Aruneshwaran_Sivakumar_Quantium_Data_Analytics_Virtual_Experience.ipynb
│
├── outputs
│   └── cleaned_qvi_data.rar      # Compressed Excel file of the cleaned data
│
├── presentation
│   └── Aruneshwaran Sivakumar_Quantium Retail Analysis.pdf
│
├── certificate
│   └── Aruneshwaran Sivakumar_Quantium Data Analytics Job Simulation_Completion certificate.pdf
│
├── requirements.txt
│
└── README.md
```
---

# Results

This project demonstrates how data analytics can be used to:

- Identify high-value customer segments
- Understand product preferences
- Evaluate retail experiments
- Support data-driven decision making in retail strategy

---

# Acknowledgement

This project was completed as part of the **Quantium Data Analytics Virtual Experience Program** hosted on the Forage platform.
This project was completed as part of the **Quantium Data Analytics Virtual Experience Program** hosted on the Forage platform.
