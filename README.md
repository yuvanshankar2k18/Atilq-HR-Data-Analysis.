📌 Problem Statement
Atliq Presence Insights – HR Data Analytics
![Atliq presence insights](https://github.com/user-attachments/assets/b9c3f8b9-4570-44a9-911f-0f749e2c2459)


🧩 Background
In today’s hybrid work model, organizations like Atliq Corp face challenges in effectively tracking:
- Employee attendance
- Work From Home (WFH) days
- Sick leaves
Without centralized insights, HR struggles to:
- Maintain workforce productivity
- Optimize scheduling

❓ The Problem
Atliq lacks a unified system to monitor and analyze presence-related data. Key issues include:
- Difficulty identifying attendance trends and absentee patterns
- No clear tracking of WFH vs. in-office behavior
- Limited visibility into day-wise and employee-wise sick leaves
- Fragmented Excel data leading to poor decision-making

🎯 Objective
Create a dynamic and visual HR dashboard that tracks:
- 📅 Attendance trends over time
- 🏠 WFH percentage and usage patterns
- 🤒 Sick leave trends
- 👤 Employee-specific presence behavior
- 📊 Day-of-week performance metrics

🛠 How to Solve It
✅ Step-by-Step Approach
1. 📂 Data Collection
- Collect raw attendance, WFH, and sick leave records
- Sources: Excel files, HRMS exports
2. 🧹 Data Cleaning
- Normalize status types (e.g., P = Present, WFH, SL = Sick Leave)
- Fill missing values with “Absent” or “0%”
- Convert date formats
- Match attendance records with employee IDs
3. 📊 Data Modeling in Power BI
- Build custom measures: Attendance %, WFH %, Sick Leave %
- Apply time intelligence for monthly and daily trend analysis
- Establish relationships between data tables (e.g., Employee ID, Date)
4. 📈 Dashboard Creation
- Include visuals: Trend lines, KPI cards, pie charts
- Add filters by date, department, and employee
- Enable comparison of attendance vs. sick leave patterns

📚 Prerequisites
To implement this solution effectively, users should have:
- 💼 Basic understanding of HR workflows
- 📊 Experience with Excel functions like VLOOKUP and Pivot Tables
- 🧠 Fundamental knowledge of Power BI (or Tableau)
- 📁 A clean and structured dataset (Excel or CSV format)

🧰 Tools Used
| Tool | Purpose | 
| Microsoft Excel | Data cleaning and formatting | 
| Power BI | Dashboard design and data visualization | 
| DAX (Power BI) | Custom KPIs and time intelligence | 
| Power Query | Data transformation and modeling | 



🧾 Conclusion
The Atliq Presence Insights Dashboard empowers HR teams by offering real-time visibility into employee attendance behavior. With visual KPIs and trend analysis, HR can:
- 📉 Reduce unplanned absenteeism
- 📅 Improve attendance planning
- 🏡 Manage WFH distribution fairly
- 🧠 Make informed, data-driven HR decisions

