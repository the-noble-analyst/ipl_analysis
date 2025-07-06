# 🏏 IPL 2022 Capstone Project

This project presents a detailed exploratory data analysis (EDA) of the **IPL 2022** season using Python. The goal is to extract valuable insights on match results, player performances, and team strategies to understand what factors influenced match outcomes.

---

## 📌 Objective

To analyze IPL 2022 match data and derive insights on:

- Most successful teams and players
- Impact of toss decisions
- Match-winning patterns (by runs or wickets)
- Player of the match trends
- Highest scores and best bowling figures
- Venue-based analysis and trends

---

## 🗂️ Dataset

The dataset used contains match-level data for IPL 2022 with 74 records and 20 columns.

**Key Columns:**
- `team1`, `team2`, `match_winner` – Team-related info
- `toss_winner`, `toss_decision` – Toss insights
- `first_ings_score`, `second_ings_score`, `margin` – Match statistics
- `player_of_the_match`, `top_scorer`, `best_bowling` – Player performance
- `venue`, `stage`, `date` – Match context

---

## 🧰 Tools & Libraries

- **Python 3.9+**
- **pandas** – data processing
- **matplotlib** & **seaborn** – data visualization
- **Jupyter Notebook** – interactive EDA

---

## 📊 Exploratory Analysis Highlights

### ✅ Most Wins by Team
- Gujarat Titans topped with **12 wins**, followed by Rajasthan Royals and Bangalore.

### 🧠 Toss Decision Insights
- Most teams chose to **field first** after winning the toss.
- Only **~49%** of toss winners ended up winning the match.

### 🏆 Player of the Match
- **Kuldeep Yadav** received the most awards (4).
- **Jos Buttler** and others followed with consistent performances.

### 🔥 Top Scorers
- **Jos Buttler** – 651 runs
- **Quinton de Kock** – 377 runs

### 🎯 Best Bowling Performances
- Best figures:  
  - **Jasprit Bumrah** – 5/10  
  - **Wanindu Hasaranga** – 5/18  
  - **Umran Malik** – 5/25  
  - **Yuzvendra Chahal** – 5/40

### 🏟️ Venue Analysis
- Most matches were played at:
  - **Wankhede Stadium (21)**  
  - **DY Patil Stadium (20)**  
  - **Brabourne Stadium (16)**  

---

## ❓ Custom Questions & Insights

- **Who won by the highest run margin?**  
  → Chennai Super Kings (91 runs)

- **Who scored the highest individual score?**  
  → **Quinton de Kock** – 140 runs

- **Which bowler had the best figure?**  
  → **Jasprit Bumrah** – 5 wickets for 10 runs

---

## 🚀 Future Enhancements

- Add IPL data from previous years for multi-year trend analysis
- Build interactive dashboards using Power BI or Plotly
- Integrate predictive models for toss or match outcome prediction

---

## 📁 Project Structure

📦 IPL-2022-Analysis/
┣ 📊 IPL.csv
┣ 📓 IPL_2022_EDA.ipynb
┗ 📄 README.md

---

## 🙋‍♂️ Author

**Nabeel Siddiqui**  
📧 nabeelsiddiqui468@gmail.com

---

## 📃 License

This project is open-source and available under the MIT License.
