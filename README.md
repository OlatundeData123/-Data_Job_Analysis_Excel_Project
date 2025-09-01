# Excel Salary Dashboard

## 📊 Data Job Analysis Dashboard

![Dashboard Screenshot](images/dashboard.png)  
*(Insert a screenshot of your Excel dashboard here)*

---

## 📖 Introduction
This project analyzes job salary data using Excel to provide insights into different roles, industries, and locations.  
The goal is to help job seekers and analysts understand trends in pay and job availability.  

The dataset used in this project comes from [Indeed](https://www.indeed.com/) and includes job postings with salary details.

---

## 🗂 Excel Skills Used
- Pivot Tables  
- Charts  
- Data Validation  
- Conditional Formatting  
- Formulas & Functions  

---

## 📁 Dataset
The dataset contains job postings with the following fields:
- Job Title  
- Company  
- Salary  
- Type (Full-time/Part-time)  
- Location  
- Skills  

---

## 🛠 Dashboard Build

### Charts
- **Median Salary by Job Title** → shows the average salary per role.  
- **Job Count by Type** → shows distribution of full-time vs part-time roles.  
- **Country/Region Heatmap** → highlights job availability globally.  

### Example
![Job Title Salary Chart](images/job_title_chart.png)

---

## 🔢 Formulas & Functions
Examples of formulas used:

```excel
=MEDIAN(IF(JobTitle="Data Analyst", Salary))
