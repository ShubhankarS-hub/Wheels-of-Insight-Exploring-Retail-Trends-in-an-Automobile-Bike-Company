# Wheels-of-Insight-Exploring-Retail-Trends-in-an-Automobile-Bike-Company
# Bike‑Retail Customer Segmentation (Python, RFM)

Data‑driven customer segmentation and sales‑insight project for an Australian bike manufacturer.  
Using Python, I cleaned raw Excel data, explored buyer behaviour, and built an **RFM model** that pinpoints high‑value riders and churn risks.

---

## Project Goals

1. Clean and unify four disparate data sources (transactions, demographics, addresses, new‑customers).  
2. Explore purchasing patterns across age, gender, industry, wealth tier and state.  
3. Segment customers via RFM (Recency, Frequency, Monetary) to reveal 11 actionable groups.  
4. Generate insights that guide revenue‑boosting campaigns and product focus.

---

## Workflow

| Step | Highlights |
|------|------------|
| **Data Audit & Cleaning** | • Dropped irrelevant fields and fixed missing values (mode/median or row removal).<br>• Standardised categorical labels and converted date fields.<br>• Engineered features: `Age`, `Age_Group`, `Profit`. |
| **Exploratory Analysis** | • Profiled customers by demographics, region, and wealth.<br>• Analysed three‑year sales trends and car‑ownership patterns. |
| **RFM Modelling** | • Computed R, F, M scores for each rider.<br>• Ranked into 11 segments (Platinum, Very Loyal, Losing, Lost, etc.). |
| **Insight Generation** | • Recency × Monetary and Frequency × Monetary plots expose value clusters.<br>• Identified 9 percent Platinum riders (55 percent revenue) and 12 percent at‑risk riders (7 percent revenue). |

---

## Key Findings

* High‑value riders (Platinum/Very Loyal) skew female, 40‑49 years, Manufacturing/Finance sectors.  
* The 30‑39 age band is under‑represented among new buyers—opportunity for targeted acquisition.  
* New South Wales shows the largest pool of non‑car owners—prime market for urban‑commuter bikes.  
* The medium‑size “Standard” line dominates purchases; upsell potential to higher‑margin variants.  

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.11** | Core language |
| **pandas** | Data wrangling and feature engineering |
| **NumPy** | Numeric operations |
| **matplotlib / seaborn** | Visual exploration and RFM plots |



