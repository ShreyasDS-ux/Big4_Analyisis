# Big4_Analyisis
Exploratory data analysis of audit, risk &amp; compliance data across the Big 4 firms (Deloitte, PwC, EY, KPMG) — covers KPIs, firm/industry/year trends, AI-vs-non-AI audit performance, fraud &amp; compliance analysis, correlations, and visualizations using pandas, NumPy, Matplotlib &amp; Seaborn.
# Big 4 Financial Risk & Compliance Analysis

Exploratory data analysis of audit, risk, and compliance data across the Big 4 accounting firms (Deloitte, PwC, EY, KPMG), built in a Jupyter Notebook using pandas, NumPy, Matplotlib, and Seaborn.

##  Overview

This project analyzes a dataset of audit engagements to uncover patterns in risk exposure, compliance violations, fraud detection, and the impact of AI adoption on audit outcomes. It moves from basic data exploration through feature engineering, filtering, KPI calculation, and grouped analysis (by firm, industry, year, and AI usage), finishing with correlation analysis and a full set of visualizations.

##  Dataset

The notebook expects a CSV file named `big4_financial_risk_compliance.csv` in the same directory, with columns including:

- `Firm_Name`, `Industry_Affected`, `Year`
- `Total_Audit_Engagements`, `High_Risk_Cases`, `Compliance_Violations`
- `Fraud_Cases_Detected`, `Total_Revenue_Impact`, `Employee_Workload`
- `Audit_Effectiveness_Score`, `Client_Satisfaction_Score`
- `AI_Used_for_Auditing`

> **Note:** The raw data file is not included in this repo. Add your own copy of `big4_financial_risk_compliance.csv` to the project root before running the notebook.

##  What's Inside

The notebook is organized into the following parts:

1. **Data Loading & Inspection** – shape, dtypes, missing values, duplicates, samples
2. **New Column Creation** – derived metrics such as Revenue Impact (Millions), Risk Ratio, Compliance Rate, Fraud Detection Rate
3. **Filtering Analysis** – firm-, industry-, and threshold-based queries (e.g. high effectiveness scores, high compliance violations)
4. **Business KPIs** – totals and averages across engagements, risk, fraud, revenue impact, and satisfaction
5. **Firm Analysis** – engagements, revenue impact, and scores broken down by firm
6. **Industry Analysis** – revenue impact, engagements, and fraud by industry
7. **AI Usage Analysis** – comparing audit effectiveness and outcomes with vs. without AI-assisted auditing
8. **Compliance & Fraud Analysis** – violation and fraud trends by firm and industry
9. **Year Analysis** – year-over-year trends in revenue impact, engagements, fraud, and compliance
10. **Top & Bottom Analysis** – top/bottom records and firms by key metrics
11. **Correlation Analysis** – relationships between workload, risk, revenue, and effectiveness, plus a correlation heatmap
12. **Visualizations** – bar charts, pie charts, histograms, scatter plots, and trend lines

##  Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install with:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

##  Usage

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/big4-financial-risk-compliance-analysis.git
   cd big4-financial-risk-compliance-analysis
   ```
2. Add `big4_financial_risk_compliance.csv` to the project root
3. Launch the notebook
   ```bash
   jupyter notebook Big_4_Analysis.ipynb
   ```
4. Run all cells

##  Key Questions Explored

- Which firms and industries carry the highest revenue impact and risk?
- Does AI-assisted auditing improve effectiveness, fraud detection, or client satisfaction?
- How do compliance violations and fraud cases trend over time?
- What's the relationship between employee workload and audit effectiveness?

##  License

This project is open source and available under the [MIT License](LICENSE).
