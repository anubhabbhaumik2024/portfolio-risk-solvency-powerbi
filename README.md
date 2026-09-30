# portfolio-risk-solvency-powerbi
End-to-end Power BI executive dashboard
# Portfolio Risk & Solvency Analysis
Academic Case Study built using anonymized loan sample data to evaluate macro origination trends, capital allocation, and top-level portfolio solvency metrics.

## 📊 Project Overview & Key Metrics
* **Total Applications Analyzed:149,000
* **Total Disbursed Volume:** $49 Billion.
* **Overall Default Rate:** 24.64% ($11.70 Billion defaulted exposure)
* **Capital Adequacy Ratio:** 76.24%
* **Risk-Adjusted Yield:** -$9.71 Billion

## 🔍 Key Findings & Strategic Insights
**Unsecured Risk Concentration:** Type 1 (unsecured credit) originations account for the vast majority of total defaulted exposure ($8.8B out of $11.7B)
**Highest Frequency Default:** Type 2 loans exhibit the highest individual default rate at 34.54%
**LTV Threshold Flag:** Key Influencer modeling confirms an LTV ratio above 107% serves as the single strongest predictor of loan default, which should be instituted as a hard underwriting cap rather than a secondary risk flag
**Stress Testing Simulation:** Stress testing confirms that tighter initial underwriting protects capital better than retroactive interest rate adjustments; enforcing a strict 60% LTV cap reduces default exposure to $6.37 billion and elevates the capital solvency rate to 87.06%.

## 🛠️ Tools & Technical Features
**Power BI:** Built utilizing custom KPI cards, scatter plots, and interactive data modeling.
**Scenario Simulation:** Implemented What-If Parameters to dynamically test how adjusting LTV cap thresholds and interest rate adjustments impact capital solvency.
**AI Visuals:** Utilized the Key Influencers visual to isolate non-linear default demographic risk thresholds.

## 📁 Repository Contents
* `Portfolio_Risk_and_Solvency_Overview.pbix` — The complete, interactive Power BI dashboard file containing the data model and visualizations.
* `Portfolio_Risk_and_Solvency_Overview.pdf` — An 8-page static export detailing the executive summary, origination analysis, exposure watchlist, and simulation results.
