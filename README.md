# 🍽️ Bengaluru Restaurant Market Intelligence

> **Submitted to Insightfy 6.0: Analytics Case Competition — IIM Lucknow**
> **Round 1 (Data Analysis & Visualization Round) · Team Maharudra · 🥇 Rank 1 Nationally · Shortlisted**

A rigorous statistical market analysis of Bengaluru's restaurant landscape —
analysing 844 restaurants across 8 localities to uncover pricing, rating,
cuisine, and location-level patterns that drive real business decisions.

---

## 🏆 Competition Context

| Field | Detail |
|---|---|
| Competition | Insightfy 6.0: Analytics Case Competition |
| Organised by | Indian Institute of Management (IIM), Lucknow |
| Event | Inflection Point 6.0 |
| Platform | Unstop |
| Round | Round 1 — Data Analysis & Visualization Round |
| Team | Maharudra — Rushikesh Kedar, Akash Bhuyan, Rahul Atkare |
| Result | 🥇 **Rank 1 Nationally** — Shortlisted for Round 2 |

**Round 1 Task (as given):**
> Perform end-to-end data processing on a restaurant dataset — rigorous
> data cleaning, handling missing values, transforming raw data into a
> structured format. Generate visual insights analysing market trends.
> Submission: cleaned dataset + summary of key findings via visualisations.

---

## 🧭 Objective

Analyse 844 Bengaluru restaurants across 8 localities to answer
real business questions:

- Does price actually predict ratings?
- Which localities are over-saturated vs. untapped?
- What drives customer ratings — and what doesn't?
- Where should a new restaurant operator enter the market?

---

## 📁 Repository Structure
```
bengaluru-restaurant-market-intelligence/
│
├── restaurant_market_intelligence.csv              # Raw restaurant dataset
├── bengaluru_restaurant_market_intelligence.ipynb  # Full analysis notebook
└── README.md
```

---

## 📦 Dataset

| Property | Detail |
|---|---|
| Restaurants analysed | 844 |
| Localities covered | 8 |
| Source | Zomato Bengaluru dataset |
| Key features | Name, location, cuisine, cost for two, ratings, votes, online order, table booking |

---

## 🔬 Methodology
```
Raw Data
   ↓
Data Cleaning — missing values, duplicates, standardisation
   ↓
Exploratory Data Analysis
   ↓
Statistical Testing (5 methods)
   ↓
15 Visualisations
   ↓
Executive Summary & Market Recommendations
```

### Statistical Methods Used

| Method | Applied To |
|---|---|
| Pearson Correlation | Price vs. Rating |
| Spearman Correlation | Votes vs. Rating |
| Mann-Whitney U | Rating: online vs. offline orders |
| Kruskal-Wallis | Rating & cost differences across localities |
| OLS Regression | Predicting ratings from multiple features |

---

## 🔑 Key Findings

### 1. 🚫 Price Does NOT Drive Ratings
> **r = −0.01** (Pearson) — near-zero correlation between cost and rating

Customers in Bengaluru do not equate price with quality.
High ratings are achievable at any price point.

### 2. 📣 Popularity ≠ Quality
High vote counts do not guarantee high ratings.
Some of the most-voted restaurants have average ratings —
visibility and quality are independent dimensions.

### 3. 📍 HSR Layout = Top Untapped Market Opportunity
Among all 8 localities, **HSR Layout** showed the strongest combination of:
- High demand with relatively low restaurant density
- Strong average ratings for existing outlets
- Low saturation compared to Koramangala and Indiranagar

> **Recommendation:** Best entry point for new restaurant operators.

### 4. 🔄 Online Ordering Significantly Impacts Votes
Mann-Whitney U (p < 0.05): Restaurants with online ordering receive
significantly more votes — directly impacting Zomato visibility.

---

## 📊 Visualisations — 15 Charts Generated

Including: distribution plots, heatmaps, locality comparisons,
cost-rating scatter plots, cuisine breakdowns, vote analysis,
OLS regression plots, and market gap charts.

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data cleaning and manipulation |
| Matplotlib / Seaborn | Static visualisations |
| Plotly | Interactive visualisations |
| SciPy | Statistical testing |
| Statsmodels | OLS regression |
| Jupyter Notebook | Development environment |

---

## 🚀 How to Run
```bash
git clone https://github.com/Rushi9234/bengaluru-restaurant-market-intelligence.git
cd bengaluru-restaurant-market-intelligence
pip install pandas matplotlib seaborn plotly scipy statsmodels jupyter
jupyter notebook bengaluru_restaurant_market_intelligence.ipynb
```

---

## 👥 Team — Maharudra

| Name | Role |
|---|---|
| Rushikesh Kedar | Statistical testing, market gap analysis, key insights |
| Akash Bhuyan | EDA, data cleaning, visualisations |
| Rahul Atkare | Locality analysis, Plotly interactive charts |

---

## 🏅 Achievement

> 🥇 **Rank 1 Nationally** — Insightfy 6.0 Analytics Case Competition, IIM Lucknow
> Shortlisted from Round 1 → Advanced to Round 2 → Reached Grand Finale
> Certificate of Participation issued via Unstop

---

## 👤 Author

**Rushikesh Baban Kedar**
B.Tech Computer Science Engineering | MIT Academy of Engineering, Pune (2023–2027)
GitHub: [Rushi9234](https://github.com/Rushi9234)
LinkedIn: [rushikesh-kedar](https://linkedin.com/in/rushikesh-kedar-87106b373)

---

## 📄 License

For academic and portfolio purposes only.
```
