# Global Superstore: Executive Sales & Profitability Dashboard

![Dashboard Preview](superstore_dashboard_preview.png)

🔗 **[View Live Interactive Dashboard (Google Looker Studio)](PASTE_LINK_LOOKER_STUDIO_KAMU_DI_SINI)**

## 📌 Business Problem
Despite strong top-line revenue growth across multiple regions, executive leadership lacked visibility into margin erosion at the sub-category level. High promotional discounts were driving sales volume while quietly generating net losses on specific product lines.

## 🛠️ Tech Stack & Workflow
* **Data Cleaning & Feature Engineering (Python / Pandas):** Standardized date formats, handled missing values, and engineered `Profit_Margin` metrics (`superstore_profitability_prep.ipynb`).
* **Data Storage & Pipeline (Google Sheets):** Structured clean flat-file dataset (`superstore_clean_bi.csv`) connected via live cloud connector.
* **Business Intelligence (Google Looker Studio):** Designed an interactive executive dashboard featuring dynamic `Region` and `Product_Category` filters, KPI scorecards, monthly revenue-vs-profit time series, and sub-category profitability rankings.

## 🔍 Key Insights & Recommendations
1. **Margin Leakage in Specific Sub-Categories:** Visualizing `Profit` sorted ascending by `Product_Sub_Category` immediately isolates loss-making items (such as Tables and Bookcases) that drag down overall company margins despite high order volume.
2. **Seasonal Revenue Spikes vs. Profit Lag:** The monthly time-series trend reveals Q4 sales surges that do not always translate into proportional net profit due to aggressive year-end discounting.
3. **Actionable Recommendation:** Cap promotional discounts at **15–20%** on underperforming sub-categories and bundle high-margin accessories with low-margin furniture items to protect net profitability.
