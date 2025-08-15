# 🏏 Cricket Match Analysis

A **data-driven cricket analytics project** covering **IPL**, **One-Day Internationals (ODI)**, and **Test matches**, using Python, MySQL, and Power BI for end-to-end data processing and visualization.

---

## 📌 Project Overview
This project processes raw cricket data from JSON files, structures it into MySQL databases, and visualizes the results in Power BI.  
The goal is to provide **match insights, player statistics, and performance trends** across multiple cricket formats.

---

## ⚡ Process Workflow

1. **Match Categories Selected**
   - IPL
   - One-Day Internationals (ODI)
   - Test Matches

2. **Database Structure**
   - `match_summary` – contains match details: date, venue, teams, toss, player of the match, etc.
   - `ball_by_ball_delivery` – contains inning, batsman runs, extras, bowler, dismissal, fielder, etc.
   - **Primary Key**: `match_id` in `match_summary`
   - **Foreign Key**: `match_id` in `ball_by_ball_delivery`

3. **Table Creation**
   - Designed and created tables with necessary columns using **VS Code** and SQL scripts.

4. **Data Extraction**
   - Sourced cricket data from the provided project website.
   - Data available in **zipped JSON** format → unzipped into a dedicated folder.

5. **Data Processing**
   - Loaded JSON data into **Pandas DataFrames**.
   - Performed data cleaning and transformation.
   - Prepared final processed data for upload.

6. **Data Storage**
   - Uploaded processed data into MySQL tables using **Python** + **VS Code**.

7. **SQL Analysis**
   - Wrote queries to generate presentation-ready insights.

8. **Visualization**
   - Built interactive dashboards in **Power BI** for each category:
     - IPL
     - ODI
     - Test Matches

---

## 🛠️ Tools & Technologies
- **Python** – Data processing
- **Pandas** – DataFrames, cleaning, transformations
- **MySQL** – Data storage
- **VS Code** – Development environment
- **Power BI** – Data visualization
- **JSON** – Raw data format

---

## 📂 Files Included

| File Name                      | Description |
|--------------------------------|-------------|
| `crick_data.ipynb`             | Python script for processing and uploading cricket data |
| `sql_queries.sql`              | SQL queries used for insights |
| `PowerBI_Dashboard.pbix`       | Power BI project file |
| `requirements.txt`             | Python libraries required |
| `README.md`                     | Project documentation |

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sethu-project/Cricket-Match-Analysis.git
   cd Cricket-Match-Analysis
