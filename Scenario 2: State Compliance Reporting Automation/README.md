# 📊 Scenario 2: State Compliance Reporting Automation

## 🔍 Background Overview
In Medicaid Managed Care, health plans are required to submit regular compliance reports to state regulatory agencies. These reports typically include performance across multiple contractually defined quality measures. Manually compiling these reports can be time-consuming and error-prone.

This scenario demonstrates how automation and data visualization can streamline compliance tracking and performance monitoring. The dashboard was designed to help internal teams quickly assess compliance performance and identify underperforming areas by measure or service category.

## 🧾 Data Structure and Initial Checks
**Source:** Simulated Medicaid performance data by measure and service category  
**Fields include:**
- `Compliance Measure`
- `Service Category`
- `Compliance Rate` (calculated field)

**Initial steps included:**
- Validating nulls and duplicates  
- Ensuring consistency in categorical values  
- Verifying that calculated compliance rates fell within a valid 0–1 range  

## 📌 Executive Summary
The overall compliance rate is **51%**, falling short of the typical 75% benchmark used by many Medicaid plans. Performance varies across compliance measures and service categories, which highlights opportunities for targeted interventions.

This Tableau dashboard helps internal stakeholders:
- Monitor overall compliance vs. target  
- Identify which measures or service areas are lagging  
- Prioritize improvement efforts on underperforming categories  

## 🔗 Dashboard Link
**[View the Tableau Dashboard on Tableau Public](https://public.tableau.com/app/profile/janine.bryant/viz/StateComplianceReportingAutomation/Dashboard1)**

## 📈 Key Insights
- **KPI 1:** The current overall compliance rate is **51%**, significantly below target.  
- **KPI 2:** Several compliance measures fall below **50%**, pulling down aggregate performance.  
- **KPI 3:** The **lowest-performing service category** has a compliance rate of just **41%**, while others exceed **54%** — suggesting an opportunity for targeted quality improvement.  

## ✅ Recommendations
- Prioritize quality improvement efforts on the **lowest-performing service category**.  
- Use this dashboard in **monthly compliance reviews** to monitor progress.  
- Incorporate **filters or drilldowns by provider group** in future iterations for deeper root-cause analysis.  

## ⚠️ Caveats
- Data is simulated and does not represent real patient or plan data.  
- Compliance rate calculations are simplified for the purpose of this prototype.  
- Time-based trends and benchmarks by region/provider are not included in this version.
