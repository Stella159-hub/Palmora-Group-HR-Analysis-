# 🌍 Palmora Group HR Analysis – Power BI Project

## 📌 Objective  
This project investigates gender-related issues within Palmora Group, a Nigerian manufacturing company, across its three regional branches. The primary goal is to analyze employee data for insights on gender distribution, pay gaps, compliance with wage regulations, and bonus allocations. The findings are aimed at guiding the company's leadership toward equitable and compliant HR practices.

---

## ❓ Questions Analyzed

1. **What is the gender distribution in the organization?**  
   - Breakdown by region and department.

2. **How do employee performance ratings compare by gender?**  
   - Identification of any trends or bias in rating patterns.

3. **What does the salary structure look like?**  
   - Detection of gender pay gaps.  
   - Identification of departments and regions requiring management focus.

4. **Does Palmora comply with the new regulation requiring manufacturing salaries to be at least $90,000?**  
   - Pay band distribution in $10,000 increments.  
   - Visualized by region.

5. **Bonus Allocation:**  
   - Bonus pay calculated based on employee performance ratings.  
   - Combined total compensation (Salary + Bonus) visualized by employee and region.

---

## 🛠️ Tools Used

- **Microsoft Power BI**  
   Used for the complete data lifecycle — transformation, modeling, DAX calculations, and dashboard visualization.

- **Power BI Data Transformation (Power Query Editor)**  
   - Removed employees without salary (assumed to have exited the company).  
   - Filtered out departments with `NULL` values.  
   - Assigned a generic gender label to employees who did not disclose gender.

- **Data Analysis Expressions (DAX)**  
   Used for calculated fields and dynamic measures, including:  
   - Average salary by gender  
   - Gender-based pay gap detection  
   - Bonus amount per rating level  
   - Salary band classification

- **Visual Analysis Techniques:**

   1. **Gender Distribution**  
      - Clustered bar charts segmented by region and department

   2. **Performance Rating by Gender**  
      - Stacked bar charts comparing rating distribution across genders

   3. **Salary Structure and Gender Pay Gap**  
      - Scatter plots showing salary distribution by gender  
      - Bar charts displaying average salary by gender across regions and departments

   4. **Salary Regulation Compliance**  
      - Histogram of employees grouped by salary bands ($10,000 intervals)  
      - Bar charts showing employees below the $90,000 requirement by region

   5. **Bonus Allocation**  
      - Bar chart of total compensation (Salary + Bonus) per employee  
      - Regional comparison of total bonus payouts

---

## 🧾 Conclusion  
The analysis revealed critical insights into gender representation, performance patterns, pay structure, and regulatory compliance. Key findings include:
- Imbalances in gender representation across departments and regions  
- Gender-based salary disparities in select areas  
- Non-compliance with the $90,000 minimum wage requirement in some manufacturing roles  
- Bonus allocations can be structured more fairly using performance-based logic

This Power BI dashboard provides a comprehensive tool for HR leadership to make data-driven decisions that promote fairness, equity, and legal compliance across Palmora Group.

---
# Palmora-Group-HR-Analysis-
An analysis of it's pay discrepancies along gender line of it's three main regions
