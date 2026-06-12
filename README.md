# 🏏 IPL Data Analysis Project (2008–2022)

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)
![SQL](https://img.shields.io/badge/SQL-SQLite-red)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)

---

## 📌 Project Overview

This project analyzes **900+ IPL matches from 2008 to 2022** to find meaningful insights about team performance, player statistics, toss impact, and venue trends using **Python and SQL**.

---

## 🎯 Objective

- Find which IPL team won the most matches
- Analyze whether winning the toss affects the match result
- Identify top performers (Player of the Match)
- Understand venue and season trends

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Main programming language |
| Pandas | Data loading and cleaning |
| Matplotlib | Charts and graphs |
| Seaborn | Advanced visualizations |
| SQLite (SQL) | Data querying |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Project presentation |
| GitHub | Version control |

---

## 📊 Key Insights

- 🏆 **Mumbai Indians** won the most IPL matches overall
- 🎯 Toss winner wins the match only **~50% of the time** — toss is NOT a big factor
- 🌟 **CH Gayle** won the most Player of the Match awards
- 🏟️ **Wankhede Stadium** hosted the most IPL matches
- 📅 Number of matches per season has been **increasing over the years**
- 🏏 Most matches are won **by wickets** rather than by runs

---

## 📁 Project Structure

```
ipl-data-analysis/
│
├── ipl_analysis.ipynb       ← Main Jupyter Notebook (Python + SQL)
├── matches.csv              ← Dataset (IPL 2008-2022)
├── ipl_dashboard.pdf        ← Power BI Dashboard (exported)
├── dashboard.png            ← Dashboard screenshot
│
├── charts/
│   ├── chart1_top_teams.png
│   ├── chart2_toss_impact.png
│   ├── chart3_top_players.png
│   ├── chart4_matches_per_season.png
│   ├── chart5_top_venues.png
│   └── chart6_win_type.png
│
└── README.md
```

---

## 📈 Charts Created

1. **Top 10 Teams by Total Wins** — Bar Chart
2. **Toss Impact on Match Result** — Pie Chart
3. **Top 10 Player of the Match Winners** — Bar Chart
4. **Matches Per Season** — Line Chart
5. **Top 5 Venues** — Horizontal Bar Chart
6. **Win by Runs vs Wickets** — Bar Chart

---

## 🗄️ SQL Queries Used

- Top 10 winning teams using `GROUP BY` and `ORDER BY`
- Toss decision analysis (Bat vs Field)
- Top Player of the Match winners
- Season-wise match count
- Most used venues

---

## ▶️ How to Run This Project

1. Clone this repository
```bash
git clone https://github.com/yourusername/ipl-data-analysis.git
```

2. Install required libraries
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Open Jupyter Notebook
```bash
jupyter notebook ipl_analysis.ipynb
```

4. Run all cells top to bottom

---

## 📊 Power BI Dashboard

The interactive dashboard includes:
- Team performance bar chart
- Toss impact pie chart
- Season trend line chart
- Top venues analysis

---

## 📚 Dataset

- **Source:** Kaggle — IPL Complete Dataset
- **Link:** https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020
- **Size:** 900+ matches across 15 seasons

---

## 👤 Author

**Your Name**
- GitHub: [@yourusernam](https://github.com/Yashaswini-Yashu7)
- LinkedIn: [Your LinkedIn](https://www.linkedin.com/feed/)

---

## ⭐ If you found this project useful, please give it a star!
