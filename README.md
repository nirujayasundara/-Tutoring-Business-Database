# -Tutoring-Business-Database
Excel project
# Excel Basic Project — Tutoring Business Database

A beginner-to-intermediate Excel data analysis project built around a realistic tutoring business database. This project demonstrates practical skills in data cleaning, Pivot Tables, Excel formulas, and business reporting — skills directly applicable to data analyst roles.

---

##  Project Structure

The workbook contains **8 data sheets** and **2 task sheets**:

| Sheet | Description |
|---|---|
| `README` | Instructions and how to use the workbook |
| `TASKS` | 20 business questions to solve |
| `Answers` | Completed answers with workings |
| `Students` | 30 student records with city and contact details |
| `Teachers` | Teacher records including monthly salary |
| `Courses` | Course catalogue with pricing |
| `Batches` | Class batches linked to teachers and courses |
| `Enrollments` | Student enrolment records with dates |
| `Payments` | Payment transactions with mode and date |
| `Sessions` | Scheduled class sessions per batch |
| `Attendance` | Student attendance records (present/absent) |

---

##  Skills Demonstrated

- **Pivot Tables** — summarising revenue, enrolments, and attendance by multiple dimensions
- **SUMIF / SUMIFS** — conditional revenue calculations
- **COUNTIF / COUNTIFS** — counting enrolments and student activity
- **SUMPRODUCT** — weighted calculations and multi-condition aggregations
- **INDEX-MATCH** — flexible lookups across related tables
- **Date-based analysis** — grouping by Month, Week, and trend analysis
- **Data Cleaning & Auditing** — identifying missing records and formatting issues across multiple related tables
- **KPI Reporting** — attendance rate, ARPU, revenue by teacher, on-time payment rate
- **Relational data thinking** — working across 8 linked tables (similar to a SQL database structure)

---

## The 20 Business Questions Answered

| No. | Question | Approach Used |
|---|---|---|
| 1 | Total number of students | COUNTA |
| 2 | Which city has the most students? | Pivot Table |
| 3 | Total revenue collected | SUM |
| 4 | Monthly revenue trend | Pivot Table (grouped by month) |
| 5 | Total outstanding fees | SUMIFS |
| 6 | Top 3 courses by revenue | Pivot Table (sorted) |
| 7 | Teacher with highest revenue attribution | Pivot Table (multi-table join logic) |
| 8 | Average class size per batch | COUNTIF + AVERAGE |
| 9 | Overall attendance rate | AVERAGE |
| 10 | Course with maximum enrolments | Pivot Table |
| 11 | Students enrolled in 2+ batches | COUNTIF |
| 12 | City with highest revenue | Pivot Table (multi-table) |
| 13 | Average course fee per course | AVERAGE |
| 14 | Weekly enrolment trend | Pivot Table (grouped by week) |
| 15 | Payment mode split % | Pivot Table (% of column total) |
| 16 | Teacher with highest gross margin | Revenue minus salary calculation |
| 17 | On-time payment rate | Date comparison formula |
| 18 | Average revenue per student (ARPU) | Total revenue / distinct paying students |
| 19 | Active students in latest month | COUNTIF on attendance |
| 20 | Next class date per batch | MIN with date condition |

---

##  Key Results

| KPI | Result |
|---|---|
| Total Students | 30 |
| Total Revenue | ₹334,500 |
| Top City by Students | Ghaziabad (7 students) |
| Top City by Revenue | Ghaziabad (₹76,500) |
| Top Course by Revenue | Class 12 Chemistry (₹120,000) |
| Overall Attendance Rate | 86.78% |
| Average Revenue Per Student (ARPU) | ₹11,150 |
| On-Time Payment Rate | 100% |
| Top Teacher by Revenue | Bushra Sahik (₹99,000) |

---

##  Tools Used

- **Microsoft Excel** (Pivot Tables, Advanced Formulas, Data Validation)
- **Power Query** (data transformation)
- **Excel Functions:** SUMIF, SUMIFS, SUMPRODUCT, COUNTIF, INDEX-MATCH, COUNTA, AVERAGE, MIN, DATE

---

##  How to Use

1. Download the file `Excel_Basic_Project_With_Database.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Start on the `TASKS` sheet to see the 20 business questions
4. Use the `Students`, `Payments`, `Enrollments` and other data sheets as your source
5. Check the `Answers` sheet to compare your solutions

---

## About This Project

This project was built as part of a data analyst portfolio to demonstrate:
- Practical Excel skills used in real business environments
- The ability to work with **relational, multi-table data** (similar to SQL databases)
- Experience identifying and handling messy or missing data
- Clear business reporting and KPI calculation

---

## Contact

**Nirosha Jayasundara**
nirujayasundara@gmail.com
[LinkedIn](https://linkedin.com/in/niroshajayasundara)
💻 [GitHub](https://github.com/nirujayasundara)
📊 [Tableau Public](https://public.tableau.com/app/profile/nirosha.jayasundara)
