<img width="1528" height="859" alt="image" src="https://github.com/user-attachments/assets/852898f3-4902-49fa-acde-23204a77b861" /><img width="1528" height="859" alt="image" src="https://github.com/user-attachments/assets/d75fa8eb-d4f3-4818-acb7-468290be7361" /># 📊 HR Intelligence: Decoding Employee Attrition
> **Transforming raw workforce data into actionable retention strategies.**

---

## 💡 The Business Case
In any organization, people are the most valuable asset. High employee turnover (attrition) isn't just an HR headache; it's an expensive business drain affecting productivity and morale. 

This project was born out of a need to move beyond "gut feelings" about why people leave. I built this **HR Analytics Dashboard** to help leadership identify high-risk segments, understand the correlation between compensation and retention, and provide data-backed recommendations to improve employee satisfaction.

---

## 🔍 Key Insights Discovered
Through this analysis, I identified several "friction points" in the employee lifecycle:
* **The "Early Career" Crisis:** Employees in the **26-35 age group** represent the highest attrition count (116). This suggests a need for better mid-level career pathing.
* **Salary Sensitivity:** There is a sharp drop in attrition once the salary crosses the **5k threshold**, indicating that the $5k mark is a critical "retention floor" for this workforce.
* **Role-Specific Vulnerability:** Laboratory Technicians and Sales Executives show the highest exit rates. This highlights a potential burnout or competitive poaching issue in technical and high-pressure roles.

---

## 🛠️ The Technical Deep-Dive
To ensure the data was clean, relatable, and performant, I utilized the following:

### 1. Data Transformation (Power Query)
* **Data Cleaning:** Handled missing values and standardized Job Roles for consistency.
* **Feature Engineering:** Created custom **Age Groups** and **Salary Slabs** to transform raw continuous data into meaningful categories for executive reporting.

### 2. Analytical Calculations (DAX)
I focused on creating **Explicit Measures** to keep the model scalable and accurate:
* **Attrition Rate:** Calculated as `(Count of Attrition) / (Total Employees)` to provide a relative metric rather than just raw counts.
* **Dynamic Slicers:** Implemented cross-filtering for Department (Sales, R&D, HR) to allow stakeholders to deep-dive into specific business units.

### 3. UI/UX Design Strategy
* **High-Contrast Aesthetics:** Chose a bold, dark-themed neon palette to ensure critical KPIs (Attrition Count & Rate) are the first thing a user notices.
* **Visual Hierarchy:** Organized the layout to flow from high-level "Big Picture" metrics at the top to granular "Root Cause" analysis (Salary, Role, Tenure) at the bottom.

---

## 📈 Impact & Recommendations
Based on the dashboard results, I proposed the following data-driven actions:
1. **Targeted Retention:** Focus on the "Upto 5k" salary bracket to stabilize entry-level roles.
2. **Engagement Programs:** Target the 26-35 age demographic to increase engagement during their most volatile career years.
3. **Internal Audits:** Conduct stay-interviews specifically for Laboratory Technicians to address the high exit volume (62).

---

## 🚀 How to View
1. Download the `.pbix` file from this repository.
2. Open in **Power BI Desktop**.
3. Explore the interactive filters for **Department** at the top right to see localized trends.

---

**Let's Connect!**
If you have questions about the data modeling or the insights derived from this project, feel free to reach out.

--> **LinkedIn:** https://www.linkedin.com/in/anwesha-chetia/
