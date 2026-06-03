# Python_Data_Analysis
# Omnichannel Retail Analytics: Decoding Consumer Behavior & Brand Performance

## 📌 Executive Summary
This repository contains an end-to-end data analytics framework evaluating over 45,000 transaction records from a multi-category retail environment. By extracting and synthesizing granular data—ranging from demographic profiles to temporal purchasing patterns—this project converts raw transactional logging into actionable market intelligence. The final outputs provide strategic recommendations for inventory optimization, targeted marketing campaigns, and brand equity enhancement.

---

## 📊 Core Data Architecture
The analysis relies on a verified, structured dataset (`transaction_ledger.csv`) tracking 12 fundamental variables across consumer interactions:

| Feature | Data Type | Operational Description |
| :--- | :--- | :--- |
| `item_id` | Alphanumeric | Unique stock keeping unit (SKU) identifier. |
| `user_id` | Alphanumeric | Unique customer account identifier. |
| `rating` | Integer (1–5) | Post-purchase customer satisfaction score. |
| `timestamp` | Datetime | Exact chronological execution of the transaction. |
| `gender` | Categorical | Customer demographic classification. |
| `category` | Categorical | Macro product division (e.g., Enterprise Electronics, Apparel). |
| `brand` | Categorical | Associated manufacturer/label. |
| `year` | Integer | Calendar year derived for time-series parsing. |
| `month` | Integer | Fiscal month derived for seasonal indexing. |
| `quantity` | Integer | Volume of units secured per transaction line. |
| `unitprice` | Float | Base financial cost per individual unit. |
| `amount` | Float | Gross transaction valuation (Quantity × UnitPrice). |

---

## 🛠️ Tech Stack & Analytical Ecosystem
* **Engine:** Python 3.11+
* **Environment:** Jupyter Notebook Ecosystem
* **Data Manipulation:** `pandas` (vectorized transformations), `numpy` (numerical arrays)
* **Data Visualization:** `matplotlib` (granular canvas design), `seaborn` (statistical distributions)

---

## 🔍 Analytical Methodology & Workflows
### 1. Data Integrity & Preprocessing
* Implemented strict type-casting routines (converting object classes to localized datetimes).
* Executed structural verification checks to confirm zero-null integrity across critical numeric features.
* Enforced operational validation rules ensuring that transaction amount directly matches quantity multiplied by unit price.
* 
### 2. Temporal Revenue Trajectories
* Aggregated gross revenue by year-over-year (YoY) and month-over-month (MoM) intervals.
* Isolated cyclical purchasing anomalies and holiday-induced volume spikes.

### 3. Demographic & Sentiment Profiling
* Evaluated gross and average customer spend across gender categories to identify purchasing power variance.
* Cross-examined review distributions against order values using statistical distribution mapping (boxplots) to check if higher-spending cohorts yield higher satisfaction.

### 4. Product Portfolio & Brand Health Diagnostics
* Ranked top-performing categories based on gross financial contribution and volume velocities.
* Isolated the top 10 market-leading brands using specialized pareto and bar-chart segmentation.

---

## 🚀 Execution & Reproducibility
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/vanguard-analytics/retail-intelligence-engine.git](https://github.com/vanguard-analytics/retail-intelligence-engine.git)
   cd retail-intelligence-engine
   # Omnichannel Retail Analytics: Decoding Consumer Behavior & Brand Performance

# Author
Clinton Odhiambo
