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
![image](https://github.com/user-attachments/assets/5541d5c7-2a2d-42e0-a0f6-6035193a16ac)
![image](https://github.com/user-attachments/assets/49162689-aca9-40b4-96dd-005e2931328c)
* The 30‑39 age band is under‑represented among new buyers—opportunity for targeted acquisition.  
![image](https://github.com/user-attachments/assets/85df1e4f-e505-4c43-8e3e-575888e444c3)

* New South Wales shows the largest pool of non‑car owners—prime market for urban‑commuter bikes.  
![image](https://github.com/user-attachments/assets/f87e61e8-ac81-4a17-9fa8-4965cfe2bb6a)

* The medium‑size “Bronze” category dominates purchases; upsell potential to higher‑margin variants.
![image](https://github.com/user-attachments/assets/d5181e93-cbb4-4e9f-90f6-76754ed6da29)
* Frequency vs Monetary and Recency vs Monetary Scatter plots as per the RFM Scores.
![image](https://github.com/user-attachments/assets/fdf44459-fc34-43ac-a09a-835a2437ad32)
![image](https://github.com/user-attachments/assets/838a0cab-d10e-44f0-b594-fa3c840e843e)



---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.11** | Core language |
| **pandas** | Data wrangling and feature engineering |
| **NumPy** | Numeric operations |
| **matplotlib / seaborn** | Visual exploration and RFM plots |



