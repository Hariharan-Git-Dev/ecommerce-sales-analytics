# Retail Transaction Intelligence Engine

## Project Overview
This project is an end-to-end Data Analytics solution designed to extract actionable business insights from a UK-based online retail dataset (540,000+ transactions). The goal of this project is to transform raw, messy transaction logs into strategic recommendations for inventory planning, customer retention, and product cross-selling.

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, MLxtend
* **Techniques:** EDA, Data Cleaning, Cohort Analysis, RFM Segmentation, Association Rules (Apriori Algorithm)

## Key Business Insights Extracted

**1. Revenue Trend & Seasonality**
* Cleaned 540k+ rows of data, removing negative quantities (returns) and missing IDs.
* Identified a massive revenue spike in **November**, indicating a strong "Holiday Shopper" effect. *Action: Supply chain must scale up inventory by October.*

**2. Customer Segmentation (RFM Model)**
* Mathematically grouped customers based on Recency, Frequency, and Monetary value.
* Identified **448 'At Risk' VIP customers**. *Action: Launch a targeted win-back email campaign offering a 20% discount to prevent churn.*

**3. Cohort Analysis & Retention**
* Built a retention heatmap revealing that the **December 2010 cohort** had a massive 50% retention rate exactly 12 months later. 
* *Action: Double the marketing acquisition budget in December, as these users yield the highest Long-Term Value (LTV).*

**4. Market Basket Analysis (Apriori)**
* Discovered that customers buying 'Dolly Girl Cutlery' have a **92% probability** of also buying 'Spaceboy Cutlery' (Lift: 12.8).
* *Action: Implement an automated "Frequently Bought Together" recommendation UI at checkout to increase Average Order Value (AOV).*

## How to View the Project
Click on the `Retail_Intelligence_Engine.ipynb` file above to view the complete Python code, data cleaning steps, and visualizations.
