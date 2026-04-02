# 👨‍💼 Employee Recommendation System (n8n Workflow)

## Project Overview
This project is an automated Employee Recommendation System built using n8n. It analyzes employee data such as performance score and attendance to categorize employees into:

-  Highly Recommended
-  Recommended
-  Not Recommended

The system also updates results into Google Sheets and visualizes insights in a dashboard.

---

##  Workflow Logic

The recommendation is based on:

- **Highly Recommended**
  - Performance Score > 85
  - Attendance > 90%

- **Recommended**
  - Performance Score between 70 – 85

- **Not Recommended**
  - Performance Score < 70

---

##  Workflow Steps

1. Trigger workflow manually
2. Fetch employee data from Google Sheets
3. Apply conditions using IF nodes
4. Categorize employees:
   - Highly Recommended
   - Recommended
   - Not Recommended
5. Merge all results
6. Append updated data into Google Sheets

---

##  Dashboard Features

- Total Employees Count
- Average Performance Score
- Highly Recommended Count
- Department-wise Performance
- Employee Recommendation Distribution
- Top Performing Employees

---

##  Tools Used

- n8n (Workflow Automation)
- Google Sheets
- Power BI (for dashboard visualization)

---

##  Project Screenshots

###  Workflow
![Workflow](workflow.png)

### Dashboard

![Dashboard](dashboard.jpeg)

---

##  Use Case

This project helps HR teams:
- Identify top performers
- Make promotion decisions
- Improve workforce planning

---

##  Author

Tiana Kumar

---

##  Future Improvements

- Add AI-based recommendations
- Real-time dashboard updates
- Employee feedback analysis
