#  🏏 IPL 2022 Comprehensive Data Analysis 

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

*An end-to-end Exploratory Data Analysis (EDA) and statistical breakdown of the Indian Premier League (IPL) 2022 season, uncovering tactical insights, venue dynamics, and player performance metrics.*

</div>

---

## 📖 Executive Summary
The **Indian Premier League (IPL) 2022** marked a historic milestone in T20 franchise cricket with the expansion to 10 teams and 74 matches. This repository houses a comprehensive data science capstone project designed to dissect the season's match-level dynamics. By applying rigorous data cleaning, aggregation, and advanced visualization techniques, this project extracts actionable insights regarding toss strategies, batting/bowling efficiencies, venue advantages, and match-winning performances.

---

## 🛠️ Tech Stack & Libraries Used

This project is built entirely in **Python**, utilizing industry-standard libraries for data manipulation, numerical computing, and statistical visualization:

| Category | Library / Tool | Description & Usage in Project |
| :--- | :--- | :--- |
| **Core Language** | Python 3.x | Primary programming language for pipeline scripting and analysis. |
| **Data Manipulation** | Pandas | Used for dataframe operations, handling missing values, data wrangling, and categorical groupings. |
| **Numerical Computing** | NumPy | Handled vectorized mathematical operations and array-based computations. |
| **Data Visualization** | Matplotlib | Core plotting library utilized for foundational figure customization and layout controls. |
| **Advanced Plotting** | Seaborn | Used for generating high-level statistical graphics (correlation heatmaps, distribution plots, and categorical bar charts). |
| **Development Environment** | Jupyter Notebook / VS Code | Interactive computing environment used for iterative analysis and narrative documentation. |

---

## 🔍 Detailed Project Workflow & What Was Done

The project follows a structured data science lifecycle to ensure robust findings:

### 1. Data Ingestion & Inspection
* Loaded match datasets (`IPL.csv`) containing 74 match records across 20 granular attributes.
* Performed initial exploratory checks (checking data types, memory usage, unique values, and missingness across features like `venue`, `toss_winner`, and `player_of_the_match`).

### 2. Data Cleaning & Feature Engineering
* **Column Standardization:** Cleaned team names, venue strings, and match outcomes to maintain consistency across aggregations.
* **Derived Metrics:** Calculated winning margins (by runs and by wickets), match venue distributions, and seasonal win-loss ratios for all 10 franchises.
* **Date-Time Parsing:** Formatted match dates to analyze temporal performance trends throughout the tournament phases (League stage vs. Playoffs/Finals).

### 3. Exploratory Data Analysis (EDA) & Statistical Breakdown
* **Franchise Performance Analysis:** Quantified total wins, loss distributions, and win percentages per team, highlighting dominant campaigns (e.g., Gujarat Titans' inaugural title run with 12 wins).
* **Toss Dynamics & Venue Advantage:** Evaluated the tactical correlation between winning the toss, electing to field/bat first, and the ultimate match outcome across venues in Mumbai and Pune.
* **Innings Progression & Scoring Trends:** Analyzed first-innings and second-innings score distributions to identify competitive par scores and pitch behaviors across different stadiums.
* **Individual Brilliance & Accolades:** Extracted top run-scorers, highest individual scores, and game-changing bowling figures, alongside frequency analysis of *Player of the Match* awards.

---

## 📂 Repository Structure

```text
ipl-2022-capstone-project/
│
├── data/
│   └── IPL.csv                    # Raw dataset containing match-by-match statistics
│
├── notebooks/
│   └── ipl_2022_analysis.ipynb    # Main Jupyter Notebook containing code, charts, and narrative
│
├── README.md                      # Project documentation (this file)
└── requirements.txt               # Python package dependencies

```
🚀 Getting Started & Installation
To run this project locally on your machine, follow these steps:

1. Clone the Repository
```
git clone [https://github.com/your-username/ipl-2022-capstone-project.git](https://github.com/your-username/ipl-2022-capstone-project.git)
cd ipl-2022-capstone-project

```

2. Set Up a Virtual Environment (Optional but Recommended)
```
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

```

3. Install Dependencies
```
pip install -r requirements.txt
(If requirements.txt is not present, install core dependencies manually:)
pip install numpy pandas matplotlib seaborn jupyter

```

4. Run the Jupyter Notebook
Launch JupyterLab or VS Code to explore the analysis step-by-step:
jupyter notebook notebooks/ipl_2022_analysis.ipynb





📈 Key Visualizations & Findings Preview

Win Distribution by Team: Visual bar plots highlighting how different franchises performed under pressure during the league stages.

Toss Decision Impact: Pie charts and count plots depicting the prevailing trend of bowling first after winning the toss in evening T20 fixtures.


