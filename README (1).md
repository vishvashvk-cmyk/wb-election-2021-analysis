# 🗳️ West Bengal Assembly Election 2021 — Data Analysis

A complete data analysis project on the **West Bengal Legislative Assembly Election 2021**, using official data from the Election Commission of India. This project explores party performance, swing seats, voter turnout patterns, and demographic trends across all 294 constituencies.

---

## 📊 Project Overview

| Detail | Info |
|---|---|
| **Election** | West Bengal Assembly Election 2021 |
| **Constituencies** | 294 |
| **Data Source** | Election Commission of India (ECI) |
| **Tools Used** | Python, Pandas, Matplotlib, Seaborn, Jupyter |
| **Key Focus** | Party performance, swing seats, turnout, demographics |

---

## 🔍 Key Findings

- **AITC won 215 seats (73.1%)** with 48.6% vote share — BJP won 77 seats with 38.4% votes
- **68 swing seats** had a margin under 10,000 votes in a direct BJP vs AITC contest — these will decide 2026
- **Dinhata** was the closest seat in the state — won by just **57 votes**
- Urban turnout (Jorasanko: 50%) was drastically lower than rural turnout (Katulpur: 90.8%)
- BJP's elected MLAs averaged **48.2 years** vs AITC's **56.9 years** — a generational gap
- SC reserved seats were nearly split: AITC 38 vs BJP 35 — the real battleground category
- CPI(M) + INC combined got 7.8% votes but **won zero seats** — first-past-the-post collapse

---

## 📁 Repository Structure

```
wb-election-2021-analysis/
│
├── WB_Election_2021_Analysis.ipynb   # Main analysis notebook
├── 10-Detailed_Results.xlsx          # Raw data from ECI
└── README.md                         # Project documentation
```

---

## 📓 Notebook Contents

The notebook is organized into 8 sections:

| # | Section | What it covers |
|---|---|---|
| 1 | Setup & Data Loading | Library imports, loading ECI Excel data |
| 2 | Data Cleaning | Removing header rows, fixing data types, handling nulls |
| 3 | Exploratory Data Analysis | Candidates per party, basic statistics |
| 4 | Party Performance | Vote share, seats won, strike rate comparison |
| 5 | Swing Seat Analysis | Margin distribution, top 20 closest seats, 2026 battlegrounds |
| 6 | Turnout Analysis | Constituency-wise turnout, urban vs rural divide |
| 7 | Demographic Analysis | Age, gender, SC/ST/General category breakdown |
| 8 | Key Insights | Summary statistics and conclusions |

---

## 📈 Sample Visualizations

- Bar charts: Party-wise vote share and seats won
- Margin distribution histogram with swing seat thresholds
- Horizontal bar chart: Top 15 closest constituencies
- Turnout distribution across 294 constituencies
- Age distribution: All candidates vs winners
- Gender pie charts: Candidates vs elected MLAs
- Category-wise (SC/ST/General) seat comparison

---

## 🚀 How to Run

### Option 1 — View directly on GitHub
GitHub renders `.ipynb` files automatically. Just click on `WB_Election_2021_Analysis.ipynb` above.

### Option 2 — Run locally

**Step 1: Clone the repository**
```bash
git clone https://github.com/your-username/wb-election-2021-analysis.git
cd wb-election-2021-analysis
```

**Step 2: Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

**Step 3: Launch Jupyter**
```bash
jupyter notebook WB_Election_2021_Analysis.ipynb
```

### Option 3 — Run on Google Colab
Click the badge below to open directly in Colab (upload the `.xlsx` file when prompted):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/wb-election-2021-analysis/blob/main/WB_Election_2021_Analysis.ipynb)

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Charts and visualizations |
| `seaborn` | Statistical plots |
| `openpyxl` | Reading `.xlsx` files |
| `jupyter` | Notebook environment |

---

## 📂 Data Source

- **Name:** Year and Constituency-wise Detailed Assembly Election Results — West Bengal 2021
- **Publisher:** Election Commission of India (ECI)
- **Link:** [eci.gov.in](https://eci.gov.in) → Past Elections → West Bengal 2021
- **Format:** Excel (.xlsx)
- **Fields:** Constituency name & number, candidate name, sex, age, category, party, general votes, postal votes, total votes, % votes polled, total electors

---

## 💡 Future Work

- [ ] Add 2016 and 2011 election data for trend analysis
- [ ] Constituency-level map visualization using GeoPandas
- [ ] Booth-level analysis using CEO West Bengal data
- [ ] Predictive model for 2026 swing seat outcomes
- [ ] Sentiment analysis from social media around 2021 election

---

## 👤 Author

**[Your Name]**  
Data Analyst | Political Data Enthusiast  
📧 your.email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).  
Data is sourced from Election Commission of India and is in the public domain.

---

*If you found this useful, please ⭐ star the repository!*
