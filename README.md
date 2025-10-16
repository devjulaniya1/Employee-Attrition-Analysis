# 📈 Employee Attrition Analysis (Excel Project)

## Project Overview

This project provides a comprehensive, data-driven analysis of employee attrition, executed entirely using **Microsoft Excel**. The primary goal was to move beyond simply calculating turnover to identify the specific demographic, performance, and temporal factors driving employee departures. The findings result in **actionable intelligence** designed to help HR professionals and management implement targeted, cost-saving retention strategies.

| Metric | Tool Used | Output | Status |
| :--- | :--- | :--- | :--- |
| **Focus** | Employee Attrition | Interactive Dashboard | Completed |
| **Method** | Advanced Excel | Strategic Recommendations | Ready for Implementation |

---

## 📂 Repository Contents

This repository contains the full project workflow, from the raw data to the final analytical solution and its extracts.

| File Name | Description |
| :--- | :--- |
| `Employee Attrition Analysis - Dataset.xlsx` | **The Original Dataset.** The raw data used as the starting point for the analysis. |
| `Employee Attrition Analysis - Solution.xlsx` | **The Complete Solution.** The final Excel workbook containing all data cleaning, derived metrics, pivot tables, charts, and the final interactive dashboard. **This is the main file for review.** |
| `_Analysis Extracts/` | Directory containing CSV extracts of the cleaned data and key pivot table outputs for quick reference. |

---

## 🛠️ Methodology: The Excel Workflow

The analysis utilized advanced Excel features (Pivot Tables, Slicers, conditional logic) to structure a robust and auditable workflow:

1.  **Data Preparation & Feature Engineering:**
    * Handled missing values and standardized column names.
    * Created crucial derived metrics: **Employee Tenure (Years)**, **Performance Groupings** (High, Medium, Low), and **Attrition Status** (Voluntary vs. Involuntary).
2.  **Core Analysis:** Used **Pivot Tables** to calculate the overall attrition rate and segmented it across key variables: Job Role, Tenure Group, Age, and Performance Rating.
3.  **Visualization & Dashboard:** Built an integrated **Dashboard** featuring line graphs for time trends and bar charts for demographic breakdowns, allowing for interactive exploration using **Slicers**.

---

## 🎯 Key Findings & Actionable Recommendations

The analysis identified three high-impact areas where retention efforts should be focused:

### 1. The Onboarding & Role Crisis

* **Observation:** Attrition is critically high in the **Laboratory Technician** role (in R&D) and among employees with **less than 2 years of tenure**.
* **Recommendation:** Implement **Targeted 'Stay Interviews'** for employees in their first 18 months, especially for high-risk roles, to proactively address workload, support, and initial career alignment.

### 2. Performance and Voluntary Push

* **Observation:** The majority of attrition ($\text{[INSERT YOUR ACTUAL PERCENTAGE, e.g., 85\%]}$) is **Voluntary**. The highest rate of departure is found among **Medium Performers**, primarily citing **lack of career growth** and **compensation**.
* **Recommendation:** Focus retention efforts on the core workforce by creating clear, documented **internal promotion pathways** specifically for the Medium Performer group.

### 3. The Seasonal Exit Trigger

* **Observation:** Attrition consistently spikes every year in **Q1 (March/April)**, indicating employees are using their annual bonus/review as a window to resign.
* **Recommendation:** **Redesign the Review Cycle.** Shift the timing of performance reviews and salary adjustments for high-turnover departments to a **mid-year cycle (Q3)**. This secures the employee's commitment for the next year *before* the Q1 attrition wave.

---

## 🚀 How to Explore the Solution

To interact with the full analysis and explore the data:

1.  Download or clone this repository.
2.  Open the file **`Employee Attrition Analysis - Solution.xlsx`**.
3.  Navigate to the **Dashboard** sheet.
4.  Use the **Slicers** provided (e.g., Job Role, Age Group) to filter the data and observe the immediate changes in the charts and key metrics.
