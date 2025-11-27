# 🏏 IPL Dashboard (2008–2024) – Microsoft Excel

## 📘 Project Overview
The **IPL Dashboard** is an interactive Excel-based analytical project that provides a complete overview of the Indian Premier League (IPL) from **2008 to 2024**.  
It visualizes team and player performances, match outcomes, boundary patterns, and franchise dominance — all powered by **Power Pivot, Pivot Tables, and Slicers** in **Microsoft Excel**.  

This project aims to bring IPL statistics to life for fans, analysts, and team strategists through **data-driven storytelling**.

---

## 📂 Dataset Source
**Dataset Link:** [Kaggle – IPL Complete Dataset (2008–2024)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

**Files Used:**
- `matches.csv` – Match-level details (season, teams, results, umpires, etc.)
- `deliveries.csv` – Ball-by-ball data (runs, wickets, extras, dismissal type, etc.)

Both files were imported into Excel and linked via **Power Pivot** using `match_id`, enabling seamless integration of match-level and ball-level data.

---

## 🧹 Data Preprocessing Steps
1. **Import & Conversion:** Imported `.csv` files into Excel and saved as `.xlsx` for Power Pivot compatibility.  
2. **Handling Missing Values:** Replaced or removed null values (umpires, winner, player_of_match, etc.).  
3. **Standardization:** Cleaned text fields (uniform team and city names).  
4. **Feature Engineering:** Added calculated fields like:
   - Total runs per team & match  
   - Win margin categories (close, moderate, large)  
   - Player-wise performance summaries  
5. **Power Pivot Linking:** Connected `matches` and `deliveries` through `match_id`.  
6. **Pivot Tables & Charts:** Created custom pivot tables to analyze wins, runs, wickets, and trends.  
7. **Slicers & Filters:** Added for Season, Team, Venue, and Match Result.  
8. **Validation:** Cross-checked derived values and relationships for accuracy.

---

## 📊 Key Dashboard Objectives

### 🎯 1. **Dynamic Season Summary**
- Overview of total runs, wickets, and top performers for any IPL season.  
- **Visuals:** KPI Cards for Total Runs, Wickets, Orange Cap & Purple Cap.  
- **Insight:** Enables season-to-season comparison of top performances.

---

### 👤 2. **Player-Specific Season Stats**
- Displays individual batsman’s total runs, 4s, 6s, and strike rate for a chosen season.  
- **Insight:** Helps analyze player consistency and impact.  
- **Visuals:** Interactive stats card using slicers.

---

### 🏆 3. **IPL Titles by Teams (2008–2024)**
- Tracks franchise success across all seasons.  
- **Visuals:** Bar Chart showing total titles per team.  
- **Insight:** Highlights dominance of MI and CSK over years.

---

### 💥 4. **Boundary Insights (Season-wise)**
- Compares total fours vs sixes per season.  
- **Visuals:** Donut or Pie Chart.  
- **Insight:** Reveals changes in batting style and pitch behavior.

---

### ⚔️ 5. **All-Time Match Wins**
- Displays total matches won by each team across IPL history.  
- **Visuals:** Bar Chart.  
- **Insight:** Identifies consistently strong teams regardless of titles.

---
## 📸 Dashboard Snapshots

### 🏠 Main Dashboard View
![Main Dashboard](https://github.com/Bhanu-danda/Ipl-Dashboard/blob/15be5466e5ff58b0ca3bf3e2042a610d0c119848/Screenshot%202025-11-10%20131419.png?raw=true)

### 🏏 Teams Page
![Teams Page](https://github.com/Bhanu-danda/Ipl-Dashboard/blob/15be5466e5ff58b0ca3bf3e2042a610d0c119848/Screenshot%202025-11-10%20131459%20-%20Copy.png?raw=true)



## 🧩 Additional Features

### 🧠 **Interactive “Teams” Page**
- Team logos & jersey colors displayed as rectangles.  
- Hover to view:
  - Number of titles won  
  - Years of championship victories  

### 📖 **“History of IPL” Sheet**
- A dedicated page summarizing the league’s origin, evolution, and milestones.  
- Accessible via a dashboard navigation button.

---

## 🧾 Conclusion
This project showcases the potential of **Excel as a data visualization and analysis tool** for sports analytics.  
It provides a 360° view of IPL data — from player achievements to franchise legacies — through an engaging, interactive dashboard.

The insights highlight:
- Team performance consistency  
- Player contribution patterns  
- Trends in scoring and gameplay evolution  

The project bridges cricket passion with data science fundamentals — perfect for fans, analysts, and professionals alike.

---

## 🚀 Future Scope
- 🔢 **Advanced Statistical Analysis** for deeper correlations  
- 🤖 **Machine Learning Models** for player & match predictions  
- 💬 **Sentiment Analysis** from fan reactions  
- 📊 **Real-time Dashboard** with live match integration  
- 🌍 **Comparative Analytics** with other global cricket leagues  

---

## 🔗 Project Links
- **GitHub Repository:** [https://github.com/Bhanu-danda/Ipl-Dashboard](https://github.com/Bhanu-danda/Ipl-Dashboard)  
- **LinkedIn Post:** [View Project on LinkedIn](https://www.linkedin.com/in/bhanu-prasad-reddy-b1431b282/)  

---
```javascript
if (isAwesome) {
  // thanks in advance :p
  starThisRepository();
}
```
