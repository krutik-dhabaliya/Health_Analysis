# 🏥 Healthcare Analysis Dashboard | Power BI
## 📌 Project Overview and Business Objectives

This project presents an interactive **Healthcare Analysis Dashboard developed in Power BI** to analyze patient demographics, hospital utilization, medical conditions, treatment patterns, and healthcare costs.

The dashboard provides stakeholders with a consolidated view of key healthcare KPIs and trends, helping them make informed operational and financial decisions.

---

### ❓ Key Business Questions

- How are patient admissions changing across financial years and hospitals?
- Which medical conditions account for the highest number of admissions?
- What are the trends in **billing amount, length of stay, and bed occupancy**?
- How do patient demographics vary by **age and gender**?
- Which admission types and insurance providers contribute most to healthcare costs?
- How do treatment and prescription patterns differ across medical conditions?

---

### 👥 Target Audience (Stakeholders)

- **Hospital Management & Administrators**
- **Healthcare Operations Teams**
- **Finance & Billing Teams**
- **Doctors and Clinical Management**
- **Healthcare Data Analysts**

---

### 🎯 Objectives of the Analysis

- Monitor key **hospital and patient KPIs** in one place.
- Identify trends in **patient admissions, treatments, and billing**.
- Understand patient demographics and prevalent medical conditions.
- Evaluate **bed utilization and length of stay**.
- Analyze healthcare costs and insurance-provider contributions.
- Support **data-driven operational and financial decision-making**.
- 
## 🧹 Data Cleaning and Transformation

The raw healthcare dataset was cleaned and transformed to ensure **data quality, consistency, and accuracy** before building the dashboard.

### 🔄 Power Query

**Power Query (M Language)** was used to clean, transform, and prepare the healthcare data for analysis.

Key transformation steps included:

- Checked and handled **missing and null values**.
- Removed **duplicate and unnecessary records**.
- Corrected and standardized **data types**.
- Standardized categorical values across the dataset.
- Created **conditional columns** based on business requirements.
- Extracted essential date parameters such as **Day, Month, and Weekday** using Power Query.
- Created derived fields for **Financial Year, Age Groups, and Length-of-Stay (LOS) buckets**.
- Prepared clean and structured data for **data modeling and DAX calculations**.
- 
### 🔗 Data Modeling

A structured data model was created in Power BI to support efficient analysis and reporting.

- Established relationships between relevant healthcare tables.
- Created a dedicated **Date/Calendar table** for time-based analysis.
- Used **DAX measures** to calculate KPIs such as admitted patients, average billing amount, bed occupancy, and length of stay.
- Implemented **Year-over-Year (YoY) comparisons** to track changes in key metrics.
- Designed the model to support interactive filtering across **financial year, month, hospital, and medical condition**.
## 📊 Dashboard Design, Insights & Business Impact

The Power BI dashboard is structured into three interactive pages, each focusing on a different aspect of healthcare performance. Interactive slicers allow users to analyze the data across financial years, hospitals, medical conditions, months, and other dimensions.

### 👥 Patient Demographics

Provides an overview of patient admissions, demographics, medical conditions, hospital performance, and key healthcare KPIs.

![Patient Demographics Dashboard](https://github.com/krutik-dhabaliya/Health_Analysis/blob/main/Output%20(Images)/P1.jpg)

### 📈 Key Trends

Focuses on admission and billing trends across weeks, months, weekdays, age groups, and admission types, along with Year-over-Year (YoY) KPI comparisons.

![Key Trends Dashboard](https://github.com/krutik-dhabaliya/Health_Analysis/blob/main/Output%20(Images)/P2.jpg)

### 💊 Treatment & Cost

Analyzes prescription patterns, insurance-provider billing, admission types, treatment costs, and Length of Stay (LOS).

![Treatment and Cost Dashboard](https://github.com/krutik-dhabaliya/Health_Analysis/blob/main/Output%20(Images)/P3.jpg)

---

### 💡 Key Insights and Business Impact

> **Filter Applied:** FY **2021–22**

- **11,228 patients** were admitted, with **100% bed occupancy** and an average **LOS of 22.53 days**.
- **Hypertension** had the highest admissions (**2,863**), followed by **Diabetes (2,781)** and **Obesity (2,573)**.
- Average billing was **$25.5K**, generating approximately **£21.6M** in total billing.
- **Elective admissions** recorded the highest average billing at **$25.8K**.
- **Medicare** contributed the highest insurance billing at approximately **£10,917K**.

**Business Impact:** These insights help track **patient demand, hospital utilization, and healthcare costs**, supporting better resource and financial planning.

---

### 🎯 Actionable Recommendations

- Optimize **Bed allocation** based on admission trends and high-demand periods.
- Closely monitor high-volume medical conditions to improve **resource and treatment planning**.
- Investigate factors contributing to higher billing for specific **admission types and treatments**.
- Use Length-of-Stay patterns to identify opportunities for improving **bed turnover and operational efficiency**.
- Track **YoY performance** regularly to identify emerging trends and areas requiring management attention.
- Review insurance-provider billing patterns to support better **financial planning and cost management**.
## 🚀 Future Improvements

The dashboard can be further enhanced by incorporating additional analytical and interactive capabilities:

- Add **patient readmission and discharge analysis** to better understand healthcare outcomes.
- Include **department-level and doctor-level performance metrics** for deeper operational insights.
- Implement **advanced drill-through and tooltip pages** for detailed analysis.
- Introduce **forecasting** to predict future patient admissions and resource requirements.
- Automate data refresh by connecting Power BI to a **live database or cloud-based data source**.
- Enhance the dashboard with additional **performance and cost-efficiency KPIs**.

---

## 🏁 Conclusion

This project demonstrates how **Power BI can transform healthcare data into meaningful and actionable insights**. Through data cleaning, modeling, DAX calculations, and interactive visualizations, the dashboard provides a clear view of **patient demographics, admission trends, hospital utilization, treatments, and healthcare costs**.

The analysis can help healthcare stakeholders monitor performance, identify trends, optimize resources, and support **data-driven decision-making**.

---

⭐ If you found this project useful, feel free to **star the repository**.
