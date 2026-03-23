# Global Data Jobs Insights Dashboard
Interactive Excel dashboard analyzing global data job postings: salaries, skills demand, remote trends, and location insights using Power Query, DAX, and Python in Excel.

![Dashboard Screenshot](screenshots/dashboard_main.png)

**Interactive Excel dashboard** exploring worldwide data analyst / data science job market trends — salaries, in-demand skills, remote work, company size, and location insights. Built as the capstone project for Luke Barousse's *Data Analayst* course.

## 🎯 Project Goals
- Clean and transform messy, real-world job postings dataset
- Build a scalable data model
- Create an interactive user-friendly dashboard
- Derive actionable insights for job seekers and recruiters

## ✨ Key Features
- **ETL pipeline** using Power Query (removed duplicates, standardized formats, split columns, calculated experience levels, etc.)
- **Data model** with relationships (Power Pivot)
- **DAX measures** for dynamic calculations (average salary, median, skill demand %, etc.)
- **Python in Excel** for advanced stats / visualizations (optional — e.g., correlation, distribution plots)
- Fully **interactive dashboard** with slicers (job title, country, experience level, remote/hybrid, etc.)

## 📊 Key Insights (examples)
- US offers the highest median salaries for data roles
- SQL remains the #1 most in-demand skill
- Remote positions often pay comparably or higher than on-site
- Senior roles show significantly higher salary ranges

## 🛠️ Tech Stack
- Microsoft Excel (desktop / 365)
- Power Query (M language) – data cleaning & transformation
- Power Pivot + DAX – data modeling & calculations
- Python in Excel – supplementary analysis & stats
- Slicers, PivotCharts, conditional formatting

## 📸 Screenshots

### Dashboard Overview
![Screenshot 2026-03-23 134612](https://github.com/user-attachments/assets/eb43115d-3003-4e77-9908-3d4966d73893)

### Power Query Transformations
![Screenshot 2026-03-23 135640](https://github.com/user-attachments/assets/29dd9f74-c246-44c0-a6d3-7347fd0a13e3)

### Data Tables/ Models
![Data Model](screenshots/data_model.png)

## 🚀 How to Use / Explore
1. Download the file: [`Data_Jobs_Analysis_Dashboard.xlsx`](Data_Jobs_Analysis_Dashboard.xlsx)
2. Open in **Excel desktop version** (best experience — some features limited in Excel Online)
3. Use the slicers on the **Dashboard** sheet to filter

## 🔍 Data Source
Based on real 2023–2024 job postings dataset used in Luke Barousse's Excel course (originally scraped / aggregated job market data).

## 📈 What I Learned
- Advanced Power Query patterns for messy real-world data
- Building efficient data models in Excel
- Writing clean, reusable DAX
- Integrating Python directly inside Excel workflows
- Designing intuitive, business-focused dashboards

## Next Steps / Potential Improvements
- Convert dashboard logic → Power BI for better sharing & mobile view
- Add time-series trend analysis (if more dated data becomes available)
- Automate data refresh with Excel + Power Automate

MIT License © Mashudu 2026
