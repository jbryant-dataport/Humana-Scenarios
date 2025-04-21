# 📊 Scenario 2: State Compliance Reporting Automation

## 🔍 Background Overview
In Medicaid Managed Care, health plans are required to submit regular compliance reports to state regulatory agencies. These reports typically include performance across multiple contractually defined measures. Manually compiling these reports can be time-consuming and error-prone.

This scenario demonstrates how automation and data visualization can streamline compliance tracking and performance monitoring. The dashboard was designed to allow internal teams to quickly understand current compliance status and identify underperforming areas by measure or service category.

## 🧾 Data Structure and Initial Checks
- **Source:** Simulated Medicaid performance data by measure and service category  
- **Fields include:**  
  - `Compliance Measure`  
  - `Service Category`  
  - `Compliance Rate` (calculated)  

Initial steps included:
- Validating nulls and duplicates
- Ensuring consistency in categorical values
- Verifying calculated compliance rates fell within a 0–1 range

## 📌 Executive Summary
The overall compliance rate is **51%**, indicating significant room for improvement across key areas. Performance varies across compliance measures and service categories, which can help guide targeted interventions.

This Tableau dashboard helps internal stakeholders:
- Monitor overall compliance
- Pinpoint which measures or service areas are lagging
- Focus improvement efforts on low-performing categories

**🔗 Dashboard Link:** [View the Tableau Dashboard on Tableau Public](https://public.tableau.com/app/profile/janine.bryant/viz/StateComplianceReportingAutomation/Dashboard1)

## 📈 Key Insights
- **KPI 1:** The current overall compliance rate is **51%**.
- **KPI 2:** One compliance measure falls below 50%, pulling down overall performance.
- **KPI 3:** The **lowest performing service category** has a compliance rate of just **41%**, compared to over **54%** in others — suggesting an opportunity for targeted quality improvement efforts.

## ✅ Recommendations
- **Focus quality improvement efforts** on the lowest-performing service category immediately to raise compliance scores.
- Use this dashboard in monthly compliance meetings to track changes over time and reallocate resources as needed.
- Incorporate drill-downs or filters in future iterations to explore performance by time or provider group.

## ⚠️ Caveats
- Data is simulated and does not represent real patient or plan data.
- Compliance rate calculations are simplified for the purpose of this prototype.
- Performance trends over time are not included in this version.
