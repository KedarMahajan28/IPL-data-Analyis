
# IPL Match Analysis Project

## Overview

**Comprehensive IPL Match Analysis Using Historical Data**

This project analyzes Indian Premier League (IPL) matches using detailed datasets from 2008–2022. The analysis involves exploring match-level as well as ball-by-ball data to uncover patterns, trends, and key insights into player performances, team strategies, and overall match dynamics.

## Project Objectives

- Analyze IPL history for patterns and insights.
- Identify top teams, players (batsmen, bowlers), best venues, and key match moments.
- Understand how tactics like toss decisions, venue choices, and innings order influence match results.
- Visualize data using graphs, charts, and dashboards for easy interpretation.

## Features/Analyses

- Venue statistics: Most matches hosted, highest scoring venues, etc.
- Team performance: Most wins, win distribution over years, influence of toss, super overs, etc.
- Player performance: Top scorers, top wicket-takers, their strike/economy rates.
- Over-wise and segment-wise (Powerplay, Middle, Death) run distributions.
- Dismissal type distributions.
- Boundaries and scoring rates by teams and players.
- Winning margins across seasons.
- Many more insights packaged as dashboards.

## Data Sources

The following data files are used (provided in project repository):

- `IPL_Matches_2008_2022.csv` — Match-level summary (date, teams, venue, toss, result, player of match, etc.).
- `IPL_Ball_by_Ball_2008_2022.csv` — Ball-by-ball details (batsman, bowler, runs, wickets, extras, etc.).



## Setup and Usage

### 1. Clone the Repository

```bash
git clone 
cd IPL-Analysis-Project
```



Install with:
```bash
pip install -r requirements.txt
```

### 3. Usage

- **Jupyter Notebooks:**  
  Open in Jupyter/Colab and run cell by cell to reproduce all explorations and visualizations.

- **Dashboards:**  
  View presentation and dashboard files in the `dashboards/` folder for summary insights.

- **Scripts:**  
  Run data cleaning and analysis scripts in `src/` for batch processing.

## Key Questions Addressed

This project answers multiple IPL-centric analytical questions, including but not limited to:

- Which venues and teams have dominated IPL history?
- Who are the top 10 run scorers and top 10 wicket takers, and what are their strike/economy rates?
- How are runs and wickets distributed across different phases (Powerplay, Middle, Death overs)?
- What are the common types of dismissals? How does toss affect outcomes?
- Which matches were the highest-scoring, and what were the biggest wins (margin)?
- Boundary counts for teams, and more!

See the `IPL_Analysis_Dashboard.pptx` for visual answers to each key question.

## Data Preparation

- All datasets have been checked for consistency (e.g., missing values, team names, dates).
- "No result" and abandoned matches have been removed for accurate statistics.
- Feature engineering performed for phase-by-phase analysis (segmenting runs/wickets by overs).

## Results and Visualizations

- Graphs, charts, and dashboards summarize all findings.
- Dominant teams: Mumbai Indians, Chennai Super Kings, etc.
- Star batsmen: Virat Kohli, David Warner, etc.
- Star bowlers: Lasith Malinga, Yuzvendra Chahal, etc.
- Venue and toss impact, scoring patterns, and more.

## How to Contribute

Contributions are welcome. Create a pull request or submit issues for bugs or suggestions.

## Authors

- Kedar Mahajan (BT23CSA033)
- Koustubh Gadekar (BT23CSA039)
- Prakhar Kothari (BT23CSA052)
- Under guidance of Mr. Santosh K Sahu



*Happy IPL analyzing!*

