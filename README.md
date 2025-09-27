# Addy-s-Employees Gender Distribution Dashboard  


This repository contains a Power BI dashboard analyzing the **gender distribution of employees** across the organization.  
It highlights overall employee counts, gender balance, and distributions by **region** and **department**.  

---

##  Objective  

The goal of this dashboard is to:  
- Measure the **overall gender ratio** in the organization.  
- Compare **male vs. female distribution** across **regions** and **departments**.  
- Identify areas with **balanced representation** and regions/departments with slight imbalances.  
- Provide insights for **diversity and inclusion monitoring**.  

---

##  Dataset Summary  

- **Total Employees:** 869  
- **Male Employees:** 448 (≈ 51.55%)  
- **Female Employees:** 421 (≈ 48.45%)  

The dataset includes employee attributes such as:  
- **Gender** (Male/Female)  
- **Location** (Regions)  
- **Department**  

---

##  Data Dictionary  

| **Field Name**        | **Description**                                                               | **Example Values**                  |
|------------------------|-------------------------------------------------------------------------------|-------------------------------------|
| **EmployeeID**         | Unique identifier for each employee (hidden in visuals, used for data integrity). | 001, 002, 003                       |
| **Gender**             | Employee gender classification.                                               | Male, Female                        |
| **Department**         | Department to which the employee belongs.                                     | Legal, Sales, Support, Training, Research |
| **Location**           | Region/office where the employee is based.                                    | Texas, Florida, Mississippi, Los Angeles |
| **NoOfEmployees**      | Total count of employees (aggregated measure).                                | 869                                 |
| **NoOfMaleEmployees**  | Total count of male employees (aggregated measure).                           | 448                                 |
| **NoOfFemaleEmployees**| Total count of female employees (aggregated measure).                         | 421                                 |

---

##  Data Source  

The dataset used in this dashboard was obtained from a **Power BI training/tutorial dataset** designed for practice and demonstration purposes.  

- **Type:** Sample HR/Employee dataset  
- **Format:** Excel file (imported into Power BI)  
- **Fields Included:** Employee ID, Gender, Department, Location, etc.  
- **Usage:** For **educational and analytical demonstration**.  
  

---

## Dashboard Insights  

### 1. Overall Gender Distribution  
- **Males:** 448 (51.55%)  
- **Females:** 421 (48.45%)  
- The gender split is **almost equal**, with a slight male majority.  

---

### 2. Gender Distribution by Region  
- **Texas:** Male – 178 | Female – 158  
- **Florida:** Male – 156 | Female – 153  
- **Mississippi:** Male – 75 | Female – 62  
- **Los Angeles:** Male – 27 | Female – 37 (female-majority)  
- **California & Carolina:** Very low representation.  

 **Insight:** Texas and Florida are the dominant employment hubs. Los Angeles is the only region where **females outnumber males**.  

---

### 3. Gender Distribution by Department  
- **Legal:** Male – 45 | Female – 31  
- **Sales:** Male – 38 | Female – 33  
- **Support:** Male – 38 | Female – 38 (perfect balance)  
- **Training:** Male – 34 | Female – 39 (female-majority)  
- **Research:** Male – 31 | Female – 36 (female-majority)  

 **Insight:** Most departments are well-balanced, with **Support** being perfectly equal and **Training/Research** leaning female.  

---

## Conclusion  

- The organization has a **healthy gender balance** (≈ 52% Male, 48% Female).  
- **No significant gender gap** exists in either regions or departments.  
- **Texas & Florida** drive the majority of employment numbers.  
- **Los Angeles and some departments (Training, Research, Business)** show **higher female participation**, highlighting strong diversity practices.  

This analysis indicates that the organization has a strong foundation in workplace gender diversity**, with room to further **enhance female representation** in high-headcount regions (Texas, Mississippi).  

---

##  Tools Used  

- **Power BI** → Data modeling & visualization  
- **Dataset** → Employee records (Gender, Region, Department)  

---

##  Next Steps  

- Extend analysis to include **gender trends over time** (e.g., hiring rates).  
- Compare gender balance with **leadership vs. non-leadership roles**.  
- Use insights for **diversity & inclusion strategy planning**.  

---
