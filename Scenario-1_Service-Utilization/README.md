# 🩺 Service Utilization Analysis: Medicaid Clinical Operations Scenario

## 📌 Background Overview
This project simulates a real-world clinical operations scenario for a Medicaid-managed care organization. The goal was to analyze how service usage and cost patterns differ by member risk level and service type — key factors that influence care coordination, outreach strategies, and resource planning.

Insights and recommendations are provided on the following key areas:

- **Utilization Trends by Risk Level:** Evaluating average paid amounts and visit volume across low, medium, and high-risk members
- **Service Type Distribution:** Identifying the most frequently used services to help prioritize care management efforts
- **Claims Efficiency:** Exploring average claims per member to detect possible overuse or underuse of care

---

## 📊 Dashboard Overview

> View the interactive dashboard here: [Tableau Public Link](https://public.tableau.com/app/profile/janine.bryant/viz/HumanaServiceUtilization/Dashboard1?publish=yes)

This Tableau Public dashboard includes the following views:

- Average Claims per Member by Risk Level  
- Average Paid per Member by Risk Level  
- Claims Volume by Service Type  
- Topline KPIs: Total Paid, Total Claims, Total Unique Members

Each chart includes dynamic comparisons and highlights how utilization shifts across risk categories. The goal is to empower Medicaid clinical operations teams with actionable insights into how their populations use care.

---

## 🗂️ Data Structure & Preparation

Data was joined from claims and member files using `Member ID`. Relevant fields included:

- **Claims Table:** `Claim ID`, `Service Type`, `Procedure Code`, `Paid Amount`, `Claim Status`, `Service Date`
- **Members Table:** `Member ID`, `Risk Level`, `Birth Date`, `Gender`, `Has Chronic Condition`, `Outreach Flag`

Key prep steps included:
- Joining datasets using Member ID
- Removing null/duplicate entries
- Creating calculated fields for:
  - Avg Claims per Member
  - Avg Paid per Member
  - Age (based on birth date)

---

## 💡 Key Insights

- **High-risk members** had the highest average paid per member — indicating more complex care needs and higher-cost services.
- **Medium-risk members** showed the highest number of claims per member, suggesting more frequent interactions with care teams.
- **Follow-up services** emerged as the most frequently billed service type across all risk groups — highlighting the importance of sustained care coordination.

---

## ✔️ Recommendations

- Focus outreach and care coordination efforts on **high-risk members** to reduce costly interventions.
- Evaluate **medium-risk service frequency** to ensure visits align with clinical best practices.
- Consider optimizing **follow-up service workflows** to streamline care and manage spend.

---

## ⚠️ Caveats and Assumptions

- Mock data was used for demonstration purposes only.
- Paid amount reflects only plan-paid dollars; patient responsibility and third-party reimbursements are excluded.
- Risk level and chronic condition flags were assumed accurate and used as primary segmentation filters.

---

## 📁 File References

| Asset | Description |
|-------|-------------|
| `Service_Utilization_Cleaned.csv` | Cleaned dataset used for dashboard creation |
| `Tableau Dashboard` | [View on Tableau Public](https://public.tableau.com/app/profile/janine.bryant/viz/HumanaServiceUtilization/Dashboard1?publish=yes) |
| `Excel Workbook` | Data prep and QA steps (optional link) |
| `SQL Queries` | (Optional - if applicable later) |

---

> Created as part of a 3-scenario GitHub portfolio to demonstrate Medicaid data analysis, visualization, and stakeholder reporting readiness.


