# HR Analytics Dashboard – Power BI Project

## 📊 Overview

This project presents an **HR analytics report** built using Power BI for a fictitious company, **Prudent Labs**. It provides the Human Resources department with actionable insights into employee dynamics, diversity, performance, and attrition trends.

The report was developed as a capstone project following my completion of several Power BI courses on **DataCamp**, including:

- Introduction to Power BI  
- Introduction to DAX in Power BI  
- Data Visualization in Power BI  
- Data Preparation in Power BI  
- Data Transformation in Power BI  
- Data Modeling in Power BI  
- Intermediate Data Modeling in Power BI

---

## 🗂️ Datasets Used

The following datasets were imported and cleaned for this analysis:

- `EducationalLevel.csv`  
- `Employee.csv`  
- `PerformanceRating.csv`  
- `RatingLevel.csv`  
- `SatisfiedLevel.csv`

Data types were verified, missing values handled, and the tables were categorized into **fact** and **dimension** tables.

---

## 🧠 Data Modeling

- Established **10 relationships** (active and inactive) across **6 tables**
- Created a **Date** table for time intelligence
- Built a dedicated **Measures** table to store DAX calculations

---

## 🔢 Key Measures

Several DAX measures were created to evaluate employee attrition and workforce structure:

- **Total Employees** – Total count of all employees  
- **Active Employees** – Count of currently active employees  
- **Inactive Employees** – Count of employees who have left  
- **Attrition Rate (%)** – Percentage of inactive employees  
  > Revealed an overall **attrition rate of 16.12%**

---

## 📈 Visualizations & Insights

### 📅 Hiring Trends  
- **Stacked Column Chart**: Hires by year & attrition status  
- Insight: Active employees rose from **116 (2021)** to **130 (2022)**

### 🏢 Department & Job Role Distribution  
- **Clustered Bar Chart**: Active employees by department  
- **Treemap**: Job roles within each department  
- Insight: **Technology** is the largest department; **Software Engineering** is the most common role

### 🌍 Diversity & Inclusion  
- **Cards**: Youngest & oldest employees  
- **Age Bins + Segmentation**: Age group by gender and attrition  
- **Pie Chart**: Marital status  
- **Bar Chart**: Avg. salary by ethnicity  
- Insights:  
  - 20–29 age group is the largest  
  - 42.45% of employees are married  
  - White employees earn the highest on average

### ⭐ Performance & Satisfaction  
- **Employee Filters**: Select individual profiles  
- **Cards**: Start date, last review, next review  
- **Charts + Table**: Performance ratings and satisfaction levels

### 🔄 Attrition Analysis  
- Visualizations of attrition by:
  - Department  
  - Job Role  
  - Hire Date  
  - Tenure  
  - Overtime  
  - Travel Frequency  
- Key Finding: **Frequent travel and overtime are strongly correlated with attrition**

---

## ⚙️ Technical Challenges & Solutions

- **Challenge**: Power BI supports only one active relationship between two tables  
- **Solution**: Used `CALCULATE()` with `USERELATIONSHIP()` to evaluate expressions using inactive relationships when needed

---

## 🌟 Power BI Features Highlighted

One of the most compelling aspects of this project is the **interactivity** of visuals. Selecting data in one chart dynamically updates others—enhancing both **explorability** and **data storytelling**.

---


