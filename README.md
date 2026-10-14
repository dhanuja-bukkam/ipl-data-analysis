# ipl-data-analysis
Exploratory data analysis of IPL ball-by-ball delivery data covering top run-scorers, boundaries, milestones, strike rates and match phases.

# IPL Data Analysis

Exploratory data analysis (EDA) of Indian Premier League (IPL) ball-by-ball data using Python. The project cleans the delivery-level dataset and visualizes batting performance across IPL history.

## Overview
The dataset contains every delivery bowled across IPL seasons, including batter, bowler, runs, extras, wickets and dismissal details. The notebook explores it to answer questions such as:
- Who are the highest run-scorers in IPL history?
- Which players hit the most fours and sixes?
- Who has scored the most half-centuries and centuries?
- How do strike rates compare across batters?
- How does scoring differ across Powerplay, Middle overs and Death overs?

## Dataset
- **File:** 'deliveries.csv' (ball-by-ball data)
- **Key columns:** 'match_id', 'inning', 'batting_team', 'bowling_team', 'over', 'ball', 'batter', 'bowler', 'batsman_runs', 'extra_runs', 'total_runs', 'extras_type', 'is_wicket', 'dismissal_kind'
- **Source:** IPL complete dataset from Kaggle

## Data Preparation
- Checked structure, data types and null values
- Standardized renamed franchises (e.g., Delhi Daredevils → Delhi Capitals, Kings XI Punjab → Punjab Kings, Royal Challengers Bangalore → Royal Challengers Bengaluru)
- Created a 'phase' feature: Powerplay (overs 1–6), Middle (7–16), Death (17–20)

## Analysis & Visualizations
- Top 20 run-scorers
- Most fours and most sixes
- Most 50s and 100s
- Batter strike rates

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

