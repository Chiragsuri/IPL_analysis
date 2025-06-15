# 📊 IPL 2024–25 Data Analysis Project

A data-driven project exploring player and team performances across the 2024 and 2025 IPL seasons — using SQL, Python, and Power BI to break down everything from boundaries and catches to team momentum and review success.

---

## 🛠️ Tools & Technologies Used

- **SQL (MySQL)** – Data filtering, transformation, and query building
- **Python (pandas, matplotlib, seaborn)** – EDA, performance analysis
- **Power BI** – Interactive dashboards with slicers, KPIs, maps, and visuals

---

## 👤 Author

**Chirag Suri**  
_Passionate about data analysis, dashboards, and cricket analytics._

- GitHub: [your-link-here]
- LinkedIn: [your-link-here]
- Portfolio: [your-site-link-here]

---

## 📁 Dataset

I used multiple datasets extracted from publicly available IPL match sources. The dataset includes:

- Ball-by-ball match details
- Player-level performance stats
- Match summary (toss, outcome, player of the match)

📎 **Source**: [*Insert dataset source link here*]

---

## 🎯 Project Goals / Problem Statements

This project aimed to answer several performance-focused and decision-making questions:

- Which players scored the most runs and took the most wickets?
- How did toss decisions influence match outcomes?
- Which teams had the best catching and fielding performances?
- Who hit the most boundaries (4s and 6s) per season?
- Which teams bowled the most dot balls?
- What were the common target ranges faced while chasing?
- How often were DRS reviews successful for each team?
- What did match outcomes look like across different venues?

---

## 🧪 Project Workflow

### 🔹 SQL Phase

- Loaded the CSV data into MySQL
- Created a filtered table (`ipl_filtered_2024_2025`)
- Cleaned match records (e.g. removed canceled match)
- Wrote queries to identify:
  - Orange & Purple Cap leaders
  - Player of the match counts
  - Strike rate & economy rankings (with filters)
  - Toss winner analysis, boundary distribution, review decisions

➡️ _File: [`IPLsql.sql`](./IPLsql.sql)_

---

### 🔹 Python + Jupyter Notebook Phase

- Imported cleaned data into pandas
- Validated data types and null values
- Created season-separated tables for better analysis
- Used matplotlib and seaborn to:
  - Plot team win % per season
  - Show total catches by teams (bar plots)
  - Visualize boundary counts, dot balls, and review success
- All visuals are export-ready and match Power BI structure

➡️ _File: [`IPL Analysis.ipynb`](./IPL%20Analysis.ipynb)_

---

### 🔹 Power BI Dashboard

Built a multi-page interactive dashboard containing:

#### 📄 Page 1: IPL Overview

- Total matches, boundaries, runs, deliveries
- Team-wise match hosting map
- Slicers for team and season

#### 📄 Page 2: Boundary & Dot Ball Insights

- Total 4s and 6s by team
- Dot balls bowled per team (per season)
- Top boundary hitters

#### 📄 Page 3: Batting Performance

- Trendline: Batting position vs runs scored
- Donut: Top 10 boundary hitters
- KPI cards: Top run scorers, strike rates

#### 📄 Page 4: Match Behavior

- Review system summary
- Target range distribution while chasing

✔️ Page navigation via buttons (no bookmarks/DAX required)

➡️ _Power BI File: [`IPL Analysis Dashboard.pbix`](./IPL%20Analysis%20Dashboard.pbix)_  
🖼️ Published version: [*Add Power BI service link here*]

---

## 📊 Key Insights

- 🏏 **Punjab Kings** led in total catches in 2025
- 🎯 Most teams chased targets between 140–179 runs
- 🥇 **V. Kohli**, **B. Sai Sudharsan** had dominant batting performances
- ⚖️ Toss winner didn't always secure match wins — strategy mattered more
- 🔄 Several matches had successful DRS overturns — DRS efficiency varies by team
- 🎯 Dot ball count helped teams control run flow, especially in 2024

---

## 💡 Things I Learned

This project taught me a lot — not just about cricket data, but about organizing a full-stack data project from scratch:

- How to set up and clean real-world data in SQL
- Structuring exploratory analysis in Python before designing visuals
- Creating clean, slicer-friendly dashboards in Power BI
- Avoiding visual clutter and focusing on **what insights actually matter**
- Balancing aesthetics with interactivity (tooltips, maps, dynamic filtering)

---

## 📦 How to Explore

If you're checking this project out:

1. You can review the `.sql` file to recreate the database
2. Use the Jupyter Notebook to experiment or modify visualizations
3. View the Power BI `.pbix` file directly, or try the online published version

---

## 📌 Résumé Summary

**IPL Data Analysis Project**  
Explored IPL 2024–25 seasons using SQL, Python, and Power BI. Built a full-stack analytics pipeline: querying match data, performing player and team-level EDA, and building an interactive dashboard showing key insights like boundaries, reviews, dot balls, and win rates.
