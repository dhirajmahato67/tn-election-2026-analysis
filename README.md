# 🗳️ Decoding the 2026 Tamil Nadu Assembly Election
### A Storytelling-First Data Analytics Project | Codebasics Resume Project Challenge

[![Power BI Dashboard](https://img.shields.io/badge/Power%20BI-Live%20Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMWNhMTFkMmItZjliNC00MGYzLTlhY2MtNjllZTlhZmVlYmE5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
[![YouTube](https://img.shields.io/badge/YouTube-Video%20Walkthrough-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@analystdhiraj)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhiraj%20Mahato-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/analystdhiraj/)

---

## 📌 Project Overview

AtliQ Media is producing a one-hour TV show on the 2026 Tamil Nadu Assembly Election results — fact-based, neutral, and data-only. As a freelance data analyst, I was tasked with finding the most compelling stories in the election data and presenting them through clean charts and a clear narrative.

> **Disclaimer:** This is a non-partisan, fact-based analysis. All data is sourced exclusively from the Election Commission of India (ECI). No political opinions, predictions, or endorsements of any kind are made.

---

## 🎯 Research Questions Explored

Out of six available research questions, I chose three and connected them into one cohesive story:

| # | Story | Question |
|---|-------|----------|
| 1 | 🔄 **The Flip Story** | In how many constituencies did the winning party change between 2021 and 2026? |
| 2 | 🗳️ **The Vote Share Story** | How did party vote shares shift state-wide and by region in 2021 vs 2026? |
| 3 | 📏 **The Margin Story** | How did the average margin of victory change between 2021 and 2026? |

---

## 📊 Key Insights

### 🔄 Flip Story
- Identified all constituencies where the winning party changed hands between 2021 and 2026
- Visualised the seat shifts using a Sankey diagram
- Uncovered regional patterns in seat flips

### 🗳️ Vote Share Story
- Compared party-wise vote share (%) state-wide across 2021 and 2026
- Broke down vote share by Tamil Nadu's six regions: Chennai Metro, North, Central, Kongu, Delta, South
- Tracked the entry and impact of new political formations

### 📏 Margin Story
- Analysed how average victory margins changed between elections
- Identified constituencies where the winner got 50%+ of valid votes
- Highlighted razor-thin contests (margin < 35%)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** (Pandas, Matplotlib, Seaborn) | Data cleaning, analysis, visualisation |
| **Power BI** | Interactive dashboard |
| **Jupyter Notebook** | Exploratory data analysis |
| **MS PowerPoint / Canva** | Presentation deck |

---

## 📁 Repository Structure

```
tn-election-2026-analysis/
│
├── README.md                        ← You are here
├── .gitignore
│
├── data/
│   ├── tn_2021_results.csv          ← 2021 TN Assembly election results
│   ├── tn_2026_results.csv          ← 2026 TN Assembly election results
│   └── constituency_master.csv      ← Constituency metadata
│
├── notebooks/
│   └── analysis.ipynb               ← Full EDA and story analysis
│
├── dashboard/
│   └── TN_Election_2026.pbix        ← Power BI dashboard file
│
└── presentation/
    └── TN_Election_2026_Deck.pdf    ← Final 8–10 slide deck
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/dhirajmahato67/tn-election-2026-analysis.git
   cd tn-election-2026-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

4. **View the dashboard**  
   Open the [live Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWNhMTFkMmItZjliNC00MGYzLTlhY2MtNjllZTlhZmVlYmE5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) in your browser, or open the `.pbix` file in Power BI Desktop.

---

## 📂 Data Sources

All data is sourced exclusively from public, official sources:

- **ECI Results Portal (2026):** [results.eci.gov.in](https://results.eci.gov.in/ResultAcGenMay2026)
- **ECI Statistical Reports:** [eci.gov.in/statistical-reports](https://eci.gov.in/statistical-reports)
- **Codebasics Starter Pack:** `tn_2021_results.csv`, `tn_2026_results.csv`, `constituency_master.csv`

> ⚠️ Exit polls, opinion polls, news articles, and social media were **not used**.

---

## 🎥 Video Walkthrough

Watch the full 5–7 minute video presentation on YouTube:  
👉 **[Decoding the 2026 Tamil Nadu Assembly Election](https://youtube.com/@analystdhiraj)**

---

## 🏆 Challenge Details

| Field | Detail |
|-------|--------|
| **Challenge** | Codebasics Resume Project Challenge |
| **Domain** | Media & Politics |
| **Function** | Data Analytics |
| **Difficulty** | Advanced |
| **Prize Pool** | ₹10,000 |

---

## 🤝 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/analystdhiraj/)
- 🐙 [GitHub](https://github.com/dhirajmahato67)
- 📊 [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWNhMTFkMmItZjliNC00MGYzLTlhY2MtNjllZTlhZmVlYmE5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

*Made with curiosity and clean data. 📊*
