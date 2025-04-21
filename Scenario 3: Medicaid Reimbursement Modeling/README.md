# 📊 Scenario 3: Medicaid Reimbursement Modeling

**Visualizing the fiscal impact of simulated rate adjustments by service category**

🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/janine.bryant/viz/MedicaidReimbursementModeling/ReimbursementModelingDashboard?publish=yes)

📄 Source Data: `Modeled_Reimbursement_Clean.csv`

---

## 🔍 Background Overview

State Medicaid programs regularly reevaluate provider reimbursement rates to ensure long-term financial sustainability and access to care. This project models the financial impact of adjusting reimbursement rates across key service categories such as Emergency Room, Primary Care, Behavioral Health, and Dental.

The goal of this dashboard is to simulate rate changes and estimate how they would affect total Medicaid paid amounts by service type.

---

## 📊 Dashboard Overview

This interactive dashboard displays total Medicaid spend by service category under current and simulated reimbursement scenarios. Users can select a new reimbursement rate using the dropdown control, and the dashboard dynamically updates to reflect projected paid amounts and fiscal impact.

### Key Features:
- **Side-by-side bar charts** show actual vs. simulated paid amounts by service category
- A **dropdown parameter control** lets users adjust the reimbursement rate (e.g., 75%, 80%, 85%, etc.)
- **Tooltips and labels** display fiscal impact (cost difference) for each category

---

## 📈 Key Insights

- **Behavioral Health** and **Primary Care** show the largest projected increases in spend under higher rate scenarios.
- **Emergency Room** services show a potential decrease in spend, simulating a policy shift toward lower acute care reimbursement.
- **Dental Services** remain flat, modeling a scenario with no rate adjustment.
- Overall fiscal impact changes dynamically based on user-selected reimbursement rates.

---

## ✅ Recommendations

- Use this dashboard to simulate future fiscal scenarios before proposing policy rate changes.
- Incorporate utilization trends to model projected volume-based costs more accurately.
- Leverage this tool to advocate for balanced rate adjustments in high-growth or high-cost areas.

---

## ⚠️ Caveats and Assumptions

- This model uses **mock data** and does not reflect actual Medicaid plan spend.
- **Rate changes are illustrative only** and not based on current policy proposals.
- Utilization volume, population growth, and seasonal trends are not reflected in this prototype.

