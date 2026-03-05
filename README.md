# 🧪 A/B Testing Analysis: Statistical Inference & Conversion Visualization

## 🎯 Project Objective
The goal of this project is to analyze the results of an A/B test using statistical methods in Python. The analysis focuses on validating the statistical significance of observed changes in key conversion metrics and providing clear visualizations for data-driven decision-making.

---

## 🛠 Tech Stack & Tools
- **Environment:** Google BigQuery (SQL), Google Colab (Python)
- **Libraries:** `Pandas`, `Statsmodels` (Z-test for proportions), `Google Cloud BigQuery`


---

### ⚙️ Automation Workflow
1. **Data Extraction:** Integrated with **Google BigQuery** to fetch raw event data (sessions, checkouts, registrations).
2. **Automated Metrics Calculation:** The script iterates through multiple test groups and target events (`add_payment_info`, `begin_checkout`, etc.).
3. **Statistical Validation:**
   - Implemented `proportions_ztest` to compare conversion rates between Control and Treatment groups.
   - Calculated **Lift %** and **P-values** to determine statistical significance.

---

## 💡 Key Deliverables
- **[🚀 Open in Google Colab](https://colab.research.google.com/drive/1BdpYxtRwRsBXGSUM-Yc1HZyJv_T8HXYb#scrollTo=MFziQ6M3QWoj)** — Full Python code.
- **[📊 View Interactive Dashboard](https://public.tableau.com/app/profile/kyrylo.rymar/viz/ABTest_17690307184180/DashboardforABTestRymarKyrylo?publish=yes)** — Visual summary of the test results.
- ![Tableau Dashboard Preview](<img width="600" height="803" alt="Dashboard_for_A_B tests" src="https://github.com/user-attachments/assets/e07e9bf7-d970-49d1-b9e6-13ee29d56f77" />)

