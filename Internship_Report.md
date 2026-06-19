# Expense Tracker with Visuals

**Name:** Harshit Dwivedi  
**Internship:** Elevate Labs — Python Developer Internship  
**Duration:** 2 Weeks  
**Project:** Expense Tracker with Visuals  
**GitHub:** https://github.com/Harshitd13/Expense-Tracker

---

## 1. Introduction

Managing personal expenses is a habit most people struggle with. Without a clear picture of where money goes each month, budgeting becomes guesswork. This project — **Expense Tracker with Visuals** — solves that problem with a Python-based web application that records expenses, visualizes spending patterns, alerts when budgets are crossed, and exports clean Excel reports. Built as part of the Elevate Labs Python Developer Internship, it demonstrates practical application of Python for real-world data problems involving data ingestion, cleaning, analysis, visualization, and reporting.

---

## 2. Abstract

The Expense Tracker is a full-featured personal finance dashboard built using Python and Streamlit. Users can log expenses through a simple form or bulk-import them via CSV. The app automatically cleans the data using Pandas — removing duplicates, fixing invalid amounts, and parsing dates. Matplotlib generates four chart types (Pie, Bar, Line trend, and Heatmap) that make spending patterns immediately clear. A budget alert system compares actual spending to a user-defined monthly limit and shows color-coded status — green for safe, yellow for warning at 80% usage, and red when exceeded. Users can export a 3-sheet formatted Excel report using OpenPyXL. The entire pipeline runs as a multi-page Streamlit dashboard with custom CSS styling for a professional, warm-toned UI.

---

## 3. Tools Used

| Tool | Version | Purpose |
|------|---------|---------|
| Python | 3.10+ | Core programming language |
| Streamlit | 1.32.0 | Web dashboard framework |
| Pandas | 2.2.1 | Data cleaning and analysis |
| Matplotlib | 3.8.3 | Chart generation |
| OpenPyXL | 3.1.2 | Excel file creation |
| VS Code | Latest | Development environment |
| Git & GitHub | — | Version control |

---

## 4. Steps Involved in Building the Project

**Step 1 — Planning and Setup:** Defined features per the project requirements (input form, CSV upload, cleaning, grouping, visuals, budget alerts, Excel export). Created project structure with virtual environment.

**Step 2 — Sample Dataset:** Built `expenses.csv` with 100+ realistic entries across 7 categories (Food, Transport, Shopping, Bills, Entertainment, Education, Health) spanning four months.

**Step 3 — Data Cleaning Module:** Wrote a `clean_data()` function using Pandas that handles missing values, invalid amounts (negative or non-numeric), unparseable dates, whitespace, and duplicate rows. Returns a summary report of cleaning operations.

**Step 4 — Expense Entry and CSV Upload:** Built a Streamlit form for manual entry with validation. Added a CSV uploader with column verification, validation metrics, and append/replace import modes.

**Step 5 — KPI Dashboard:** Computed key metrics — Total spent, current month spending, top spending category, and average transaction size. Displayed as custom-styled KPI cards with accent borders.

**Step 6 — Visualizations:** Created four Matplotlib charts: Pie chart for category share, horizontal Bar chart for category totals, Line chart for monthly trend, and Heatmap for month-by-category breakdown. Added category and date range filters.

**Step 7 — Budget Alert System:** Implemented budget comparison with three states — green (within budget), yellow (over 80% used), and red (exceeded). Added optional per-category budgets with progress bars.

**Step 8 — Excel Export:** Built `export_to_excel()` using OpenPyXL to generate a 3-sheet Excel file (All Expenses, By Category, By Month) with formatted headers, alternating row colors, borders, and auto-fitted column widths.

**Step 9 — UI Design:** Applied custom CSS for a warm, cohesive color palette (cream backgrounds, rust accents, cocoa sidebar). Replaced default Streamlit radio buttons with custom session-state navigation for better visual control.

**Step 10 — Testing and Deployment:** Tested every page with edge cases (empty data, invalid CSV, duplicate entries). Took screenshots, wrote README, pushed to GitHub.

---

## 5. Conclusion

The Expense Tracker with Visuals successfully meets every requirement outlined in the internship project brief — input form, CSV upload, data cleaning, grouping by category and date, visualizations (pie/bar/line/heatmap), budget alerts, and Excel export. Beyond the basics, it includes filtering, search, multi-page navigation, and a polished UI. The project demonstrates end-to-end Python skills relevant to data analytics and developer roles. Future improvements could include database integration, user authentication, recurring expense automation, and AI-based spending predictions. This project gave me hands-on experience with Streamlit, Pandas data pipelines, Matplotlib customization, and OpenPyXL formatting — all directly applicable to real-world Python development work.