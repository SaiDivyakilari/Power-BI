# Data Professional Survey Breakdown - Power BI Dashboard

This Power BI project presents insights from a survey of 630 data professionals. It visualizes trends in salary, programming preferences, job satisfaction, and demographics using a clean and interactive dashboard.

## 📊 Dashboard Overview

The dashboard answers key questions:
- 🌎 **Country Distribution** of survey participants.
- 💼 **Average Salary** per job title (Data Scientist, Data Engineer, etc.).
- 👩‍💻 **Favorite Programming Languages** by role.
- 🎯 **Difficulty in Breaking into Data** (Very Easy to Very Difficult).
- 😊 **Job Satisfaction Rating** (scale 0–10).
- ⚖️ **Work-Life Balance Rating** (scale 0–10).
- 📊 Filters available for **Job Title** and **Gender**.

## 🔧 Data Transformation Summary

The data was cleaned and transformed in Power Query using the following steps:
- Removed blank rows and unnecessary columns
- Merged `Date` and `Time` columns
- Changed data types for consistency
- Split columns for roles and programming languages using delimiters
- Replaced null/irrelevant values
- Duplicated and modified salary fields to create average salary metrics
- Created custom columns for analysis (e.g., difficulty level, salary ranges)
- Reordered and renamed columns for clarity
- Used multiple `Split Column by Delimiter` and `Changed Type` operations

Over **30 transformation steps** were performed to shape the data for optimal reporting.

## 📁 Project Files

- `Power Bi Project.pbix` – Main Power BI file containing all visuals and data model

## 💡 Key Insights

- **Most represented countries**: United States, India, and Others
- **Top-paying role**: Data Scientist
- **Top language**: Python
- **Overall job satisfaction**: 4.27 / 10
- **Work-life balance**: 5.74 / 10
- **Breaking into data**: Mixed difficulty, with many rating it as "Easy" or "Difficult"

## 🛠 Tools Used

- Power BI Desktop
- Power Query (M Language for transformations)

## 📌 How to Use

1. Open `Power Bi Project.pbix` in Power BI Desktop.
2. Explore each visual using filters to segment by role, gender, etc.
3. Modify queries or visuals for deeper insights or customization.


