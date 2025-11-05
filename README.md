# 🩺 Referral to Recovery: A Power BI Dashboard Analysis of Service Performance

**Author:** Oluwaseyi Fatuase  
**Role:** Data Analyst | Power BI Developer  
**Email:** [analystseyi@gmail.com](mailto:analystseyi@gmail.com)  
**LinkedIn:** [linkedin.com/in/oluwaseyi-fatuase-16009b161](https://www.linkedin.com/in/oluwaseyi-fatuase-16009b161/)  

---

## 🧭 Stakeholder Requirement
This dataset contains details of referrals and discharges for a community healthcare service over a six-month period.  
The stakeholder requested an analysis to support the service in evaluating performance against the following targets:

- **Waiting Times Target:** Patients should begin treatment within **18 weeks** of referral.  
- **Recovery Target:** At least **50%** of discharged patients should achieve recovery.  

The analysis should highlight key insights, trends, and data quality issues, using Power BI visualizations to support evidence-based recommendations.  
This document summarizes the findings from the Power BI dashboard created to address these stakeholder requirements.

---

## 🖥️ Power BI Dashboard Overview
The interactive **Power BI Dashboard** allows users to explore the data dynamically — every visual element, including text components, is **clickable and filterable**.  
Users can drill down into time periods, referral reasons, and recovery outcomes for deeper insights.  

A **static image preview** of the dashboard is provided below for reference:  
📸 [**View Dashboard Image Preview**](Dashboard_Screenshots/Dashboard.jpg)  

> _Note: The actual Power BI dashboard is dynamic — all visuals are interactive, enabling filtering, cross-highlighting, and time-based exploration._  

---

## 1️⃣ Treatment Commencement Completeness
**Insight:**  
Of **11,501 total patients**, only **7,954 (69.16%)** had a recorded treatment commencement date, leaving **30.84% unrecorded**. This suggests that nearly one-third of patient treatment data is incomplete, which can impact accurate reporting on treatment initiation rates, performance tracking, and care continuity. This incomplete data impedes accurate performance analysis.

**Recommendation:**  
- Enforce mandatory data capture for treatment commencement.  
- Introduce dashboards to flag missing treatment start records.  
- Conduct staff retraining on data entry and process compliance.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 2️⃣ Referral Volume Trend (January–June)
**Insight:**  
All referrals were received within six months from January to June. Referral numbers rose from **1,767 in January** to a **peak of 2,159 in March**, dipped slightly in April, and rose again to **2,038 by June**. This indicates fluctuating demand early in the year with a stable upward trend in midyear.

**Recommendation:**  
- Monitor referral patterns to align staffing and capacity during high-demand months.  
- Investigate causes of referral spikes (e.g., seasonal trends or campaigns).  
- Develop predictive dashboards to anticipate referral fluctuations.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 3️⃣ Most Common Reason for Referral
**Insight:**  
The most frequent referral reason is **“No Record”**, accounting for **34.71% (3,992 of 11,501)**. This highlights a significant data completeness issue, limiting the ability to identify actual reasons for referral.

**Recommendation:**  
- Make “Referral Reason” a mandatory data field.  
- Conduct regular data audits to identify missing entries.  
- Provide staff training on accurate data input.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 4️⃣ On-Time Treatment Rate (Within 18 Weeks)
**Insight:**  
Among patients with a recorded commencement date, **86.41%** completed treatment within **18 weeks (6,873 of 7,954)**. However, considering all patients, only **59.76%** met the 18-week target. While recorded cases show strong adherence to the target, the unrecorded or delayed cases lower the hospital’s overall on-time treatment rate. This gap indicates incomplete data and delayed treatment starts impact performance results.

**Recommendation:**  
- Improve data completeness to reflect true on-time rates.  
- Implement real-time alerts for cases approaching the 18-week threshold.  
- Review scheduling efficiency and staff capacity to minimize delays.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 5️⃣ 18-Week Wait Time Trend (January–November)
**Insight:**  
The percentage of patients starting treatment within 18 weeks **peaked at 100% in April and May**, then **declined steadily** to just **5.03% by November**. This sharp decline signals worsening timeliness and possible capacity strain in the latter half of the year.

**Recommendation:**  
- Analyze operational or resource constraints from midyear onward.  
- Apply load balancing and capacity planning strategies.  
- Introduce monthly KPI tracking dashboards to spot declining trends early.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 6️⃣ Best Recovery Rate by Referral Reason
**Insight:**  
Patients referred for **Mixed Anxiety and Depressive Disorder** achieved the **highest recovery rate at 60%**, outperforming other conditions. This suggests effective treatment methods and strong patient engagement for this group.

**Recommendation:**  
- Analyze successful interventions used in these cases.  
- Replicate best practices across lower-performing conditions.  
- Maintain regular outcome monitoring for sustained improvement.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 7️⃣ Discharge Eligibility and Overall Recovery
**Insight:**  
Only **2,880 of 11,501 patients (25%)** were eligible for discharge, with a **52.74% recovery rate** among them (**1,519 recovered**). While the recovery rate for discharged patients is moderate, the low proportion of discharge-eligible records suggests incomplete discharge documentation or possible gaps in patient follow-up recording. This limits the ability to assess true recovery outcomes across the entire patient population.

**Data Quality Concerns:**  
- Missing discharge and recovery data for 75% of patients.  
- Inconsistent data entry across sites or teams.
  
**Recommendation:**  
- Conduct comprehensive data quality reviews.  
- Standardize discharge procedures and ensure full data capture.  
- Implement validation rules and automated data checks in Power BI.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## 8️⃣ Recovery Rate Trend (January–December)
**Insight:**  
Recovery rates began around **45–50% early in the year**, peaked near **67% in May**, and declined to about **40% by December**. The downward trend implies possible reductions in treatment effectiveness or patient follow-up quality.

**Recommendation:**  
- Identify factors driving post-midyear decline (e.g., staffing, treatment duration).  
- Strengthen post-treatment follow-up processes.  
- Use predictive analytics to flag high-risk non-recovery cases.  

📊 **Insert Dashboard Screenshot Here**  
`![18 Week Wait Trend](Dashboard_Screenshots/18_week_trend.png)`

---

## Highlighting Data Quality Issues and Recommendations to the Service Lead

**Key Observations:**  
- Only **2,880 out of 11,501 patients (25%)** were eligible for discharge.  
- Of these, **1,519 patients (52.74%) recovered**, meeting the 50% target **only among discharged patients**.  
- **75% of patients** lack discharge eligibility status — a major **data completeness issue**.

**Data Quality Concerns:**  
- Missing referral reasons (“No Record” = 34.71%).  
- Missing treatment commencement data (30.84% unrecorded).  
- Missing discharge and recovery documentation for 75% of patients.

**Recommendations:**  
- Perform **data quality audits** and enforce **standardized recording** practices.  
- Implement **data validation rules** and make key data fields **mandatory**.  
- Introduce **Power BI completeness dashboards** to monitor data accuracy by team or month.  
- Provide **training and accountability frameworks** for staff responsible for data entry.  

📊 **Insert Dashboard Screenshot Here**  
`![Data Quality Overview](Dashboard_Screenshots/data_quality_issues.png)`

---

## 5️⃣ Presenting Insights to Different Audiences
| **Audience** | **Focus** | **Presentation Style** |
|---------------|-----------|------------------------|
| **Executives / Senior Management** | Strategic KPIs, overall trends, and improvement impact | High-level dashboards with summary metrics and short recommendations |
| **Clinical Leads / Managers** | Service delivery performance and operational detail | Interactive Power BI visuals with drill-down capability |
| **Data Quality / Governance Teams** | Data completeness and consistency | Detailed tables, validation metrics, and audit trends |
| **Frontline Staff** | Importance of accurate data entry and outcomes tracking | Simplified visuals and examples showing real-world impact |
| **External Regulators / Commissioners** | Compliance with targets (18-week & 50% recovery) | Formal reports with benchmarks, KPIs, and trend visualizations |

---

## 🧠 Overall Summary
This analysis shows that while discharged patients meet the 50% recovery target, incomplete data significantly limits visibility of total service performance.  
On-time treatment rates and recovery outcomes **decline over time**, indicating operational challenges and inconsistent data entry.  

**Key Actions for the Service:**
1. Improve **data completeness** across all core performance metrics.  
2. Enhance **operational planning** to sustain 18-week target performance.  
3. Embed **real-time data validation and monitoring** in Power BI.  
4. Ensure **regular feedback** between analytics, management, and clinical teams.

---

## ⚙️ Tools & Skills Demonstrated
- **Power BI:** Data modeling, DAX measures, KPI visuals, and dashboard design.  
- **Data Analysis:** Trend identification, benchmarking, and performance tracking.  
- **Data Quality Management:** Missing data detection and completeness analysis.  
- **Storytelling with Data:** Translating metrics into actionable recommendations.  
- **Healthcare Analytics:** Monitoring referral-to-recovery patient journeys.

---

## 🧾 Conclusion
This Power BI analysis demonstrates how visual analytics can transform raw healthcare data into actionable insights.  
By improving data quality, monitoring KPIs consistently, and applying data-driven decision-making, healthcare services can strengthen both operational efficiency and patient outcomes.

---

### 👤 Author
**Oluwaseyi Fatuase**  
*Data Analyst | Power BI Developer*  
📧 [analystseyi@gmail.com](mailto:analystseyi@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/oluwaseyi-fatuase-16009b161/)
