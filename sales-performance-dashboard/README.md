# Industrial Supply Sales Performance Dashboard

An interactive dashboard that turns 35,000 raw B2B sales records into a clean, automated tracking tool.

---

## Project Overview

- **Goal:** Replace messy spreadsheets with a central hub that tracks 12 months of wholesale sales data.
- **Focus:** Interface clarity, seasonal demand tracking, and clean layout design.
- **Output:** Fully interactive dashboard report and a detailed case summary document.

---

## Technologies Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Python (Mock Data Generation)
- Excel

---

## Problem

Wholesale distributors sell high-value items like structural steel and heavy machinery. Traditionally, managers tracked these sales using long, text-heavy spreadsheets. This manual setup made it hard to spot sudden drops in sales, see regional shifts, or catch excessive discount leaks before they hurt company profits.

---

## Solution

The solution focused on visual structure and immediate clarity:

- **Centralized Data Engine:** Cleaned and organized inconsistent spreadsheet grids using automated Power Query rules.
- **Clean Grid Interfaces:** Built an easy-to-read layout using Gestalt principles (Proximity, Similarity, and Continuity) to reduce visual clutter.
- **Intentional Color Coding:** Programmed simple color flags to point a manager's eyes straight to the most important data trends instantly.

---

## Tools Used

- **Power BI Desktop**
  - Built the interactive layout grid, connected the visuals, and set up the filtering paths.
- **Power Query**
  - Cleaned the raw rows, removed duplicate entries, and created chronological sorting columns.
- **DAX (Data Analysis Expressions)**
  - Wrote custom formulas for business totals (Total Sales, Gross Profit Margin) and set up chart highlight colors.
- **Python**
  - Programmed a 35,000-row transactional baseline to simulate real-world seasonal sales shifts.

---

## Key Features

- **Top Executive KPI Cards**: Four clean boxes showing Total Revenue (₱67.20M), Net Profit (₱13.17M), Orders (35,000), and Average Order Value (₱1.92K).
- **Monthly Sales Trend Line**: A 12-month timeline chart built to spot busy seasons and seasonal drops instantly.
- **Sales Contribution Donut Chart**: A clean ring chart that compares online government portal bidding (PhilGEPS) against physical showrooms.
- **Discount Distribution Histogram**: An automated chart that counts how often specific price cuts are given out.
- **Proximity Filter Toolbar**: A compact control panel clustered at the top that lets users filter data instantly.

---

## Challenges

- Using conditional DAX code to automate chart colors so charts don't look overwhelming.
- Fixing alphabetical calendar bugs in data graphs by using a helper index column to sort months correctly.
- Maximizing chart readability by turning off messy gridlines and redundant axis titles.
- Keeping the dashboard responsive and fast when filtering a large, 35,000-row dataset.
- Aligning layouts with human sight habits (Gestalt principles) so the data tells a natural story.

---

## What I Learned

- Converting long, confusing lists of numbers into clean visual cards that tell an immediate story.
- Using Gestalt grouping rules to place filters right next to charts for a more natural user workflow.
- Designing with strict ethical rules, like locking chart axes to absolute zero to prevent data distortion.
- Writing functional DAX metrics to calculate growth and margin metrics under tight deadlines.
- Cleaning chronological sorting issues quickly using simple data transformation steps.

---

## My Contributions

- Programmed the **data cleaning, field verification, and text sorting rules** in Power Query.
- Built a **chronological month sorting system (Month.1 helper column)** to fix timeline graphs.
- Authored the **live business math and color-logic calculations** using custom DAX formulas.
- Designed the end-to-end **dashboard theme, layout frames, and interactive grids** using Gestalt principles.

This project was developed as a solo requirement for Data Visualization.

---

## Prototype

🔗 [View Data Analytics Report PDF](./sales-analytics-report.pdf)

---

## Future Improvements

- Connect the model to live cloud nodes for hands-free, real-time database updates.
- Use automated trend forecasting lines to help anticipate inventory spikes before busy seasons.
- Implement Row-Level Security (RLS) paths so regional offices can only view their own local metrics.

---

## License

This project is for academic and portfolio purposes only.
