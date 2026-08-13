# 🎬 Netflix Power BI Dashboard — Internship Project

An end-to-end Power BI project analyzing Netflix's content library — covering data cleaning, KPI reporting, geographic analysis, trend analysis, and audience/category intelligence.

## 📌 Project Overview

This project was built as part of a Power BI internship, using a Netflix content dataset (movies and TV shows) to design a multi-page interactive dashboard with a custom dark "Netflix-style" theme.

## 🗂️ Dataset

- **Source file:** `Dataset.csv`
- **Cleaned file (Google Drive):** [Dataset_cleaned.csv](https://drive.google.com/drive/my-drive/DatasetDashboard)
- **Rows:** 8,790
- **Columns:** `show_id`, `type`, `title`, `director`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`

## 🛠️ Tools & Skills Used

- Power BI Desktop
- Power Query (data cleaning & transformation)
- DAX (measures and calculated columns)
- Data Modeling
- Data Visualization & Dashboard Design

## ✅ Tasks Completed

### Task 1 — Data Preparation & Power BI Setup
Imported and cleaned the dataset using Power Query. Fixed a data quality issue caused by an embedded line break in the `title` field (which had shifted values across columns), set correct data types for each column, and validated row counts for accuracy.

### Task 2 — Netflix Content Overview Dashboard
KPI cards (Total Titles, Total Movies, Total TV Shows, Movie %, TV Show %), a donut chart for Movies vs TV Shows, a bar chart of top content categories, a column chart of titles by rating, and interactive slicers.

![Task 2 - Content Overview Dashboard](screenshots/Task2.png)

### Task 3 — Global Content Insights Dashboard
A filled map showing content distribution by country, a matrix with country-wise Movies/TV Shows/Total breakdown, a bar chart ranking the top 10 countries by content volume, and interactive filters.

![Task 3 - Global Content Insights Dashboard](screenshots/Task3.png)

### Task 4 — Content Growth & Trend Analysis
Line charts tracking content growth by release year (with trend line) and a Movies vs TV Shows trend comparison, a column chart of content added by year, and a YoY Growth % DAX measure.

![Task 4 - Content Growth & Trend Analysis](screenshots/Task4.png)

### Task 5 — Audience & Content Category Intelligence
A custom `audience_segment` column (Kids / Family / Teens / Adults) derived from content rating, DAX measures for segment-wise content counts and % mature content, a donut chart of audience segmentation, and a category-vs-audience-segment matrix.

![Task 5 - Audience & Content Category Intelligence](screenshots/Task5.png)

## 🎨 Design

All dashboard pages follow a consistent **dark, Netflix-inspired theme**:

| Element | Color |
|---|---|
| Background | `#141414` |
| Card / chart surface | `#1A1A1A` |
| Primary accent | `#E50914` (Netflix red) |
| Secondary data | `#B3B3B3` |
| Text | `#FFFFFF` |

## 🚀 How to Open This Project

1. Clone or download this repository
2. Open `Netflix_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft)
3. If prompted, update the data source path to point to `Dataset.csv` (or the cleaned version linked above)

## 📖 Key Learnings

- Power BI fundamentals and the Power Query Editor
- Data cleaning and handling malformed CSV rows
- DAX measures and calculated columns
- Dashboard design principles and custom theming
- Geographic, trend, and audience-segmentation analysis

## 👤 Author

Muhammad Suffian 
Internship Project — Power BI Data Analytics
