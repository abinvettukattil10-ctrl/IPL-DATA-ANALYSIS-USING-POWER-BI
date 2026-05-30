# IPL Data Analysis Dashboard 🏆

## Overview
This project presents an interactive **Indian Premier League (IPL) Data Analysis Dashboard** developed using **Microsoft Power BI**. The dashboard provides comprehensive insights into IPL matches, teams, players, and tournament statistics, enabling users to explore performance trends and key cricket analytics through dynamic visualizations.

## Project Objectives
- Analyze IPL match results across seasons.
- Evaluate team performance and winning trends.
- Identify top-performing batsmen and bowlers.
- Explore venue-wise and season-wise statistics.
- Visualize key IPL metrics through interactive dashboards.

---

## Dataset

The dataset includes historical IPL match and ball-by-ball data containing:

### Match Data

| Column Name | Description |
|-------------|-------------|
| id | Match ID |
| season | IPL Season |
| city | Match Venue City |
| date | Match Date |
| team1 | Team 1 |
| team2 | Team 2 |
| toss_winner | Toss Winning Team |
| toss_decision | Bat/Bowl Decision |
| winner | Match Winner |
| player_of_match | Man of the Match |
| venue | Stadium Name |

### Delivery Data

| Column Name | Description |
|-------------|-------------|
| match_id | Match Identifier |
| inning | Innings Number |
| batting_team | Batting Team |
| bowling_team | Bowling Team |
| batsman | Batsman Name |
| bowler | Bowler Name |
| batsman_runs | Runs Scored |
| total_runs | Total Runs |
| player_dismissed | Wicket Information |
| dismissal_kind | Type of Dismissal |

### Dataset Source
IPL datasets are commonly available from Kaggle, Cricbuzz archives, and public cricket statistics repositories.

---

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV Files
- Data Modeling & Visualization

---

## Data Cleaning & Transformation

The following preprocessing steps were performed:

- Removed duplicate records.
- Handled missing values.
- Standardized team names across seasons.
- Created relationships between Match and Delivery tables.
- Generated calculated measures using DAX.
- Created season-wise and team-wise aggregations.

---

## Dashboard Features

### 📊 Executive Summary
- Total Matches
- Total Teams
- Total Seasons
- Total Runs Scored
- Total Wickets Taken

### 🏆 Team Performance Analysis
- Matches Played
- Matches Won
- Win Percentage
- Season-wise Performance Trends

### 🏏 Batting Analysis
- Top Run Scorers
- Highest Individual Scores
- Strike Rate Analysis
- Boundary Distribution (4s & 6s)

### 🎯 Bowling Analysis
- Leading Wicket Takers
- Economy Rate Comparison
- Bowling Performance by Season

### 🏟 Venue Analysis
- Matches Hosted by Venue
- Average First Innings Score
- Venue-wise Win Trends

### 📅 Season Analysis
- Season Champions
- Total Runs per Season
- Total Wickets per Season
- Season Growth Trends

### 🔍 Interactive Filters
- Season
- Team
- Venue
- Player
- Match Type

---

## Key KPIs

| KPI | Description |
|------|-------------|
| Total Matches | Number of IPL Matches |
| Total Runs | Runs Scored Across Seasons |
| Total Wickets | Total Wickets Taken |
| Highest Team Score | Maximum Team Total |
| Most Successful Team | Team with Most Wins |
| Orange Cap Leader | Highest Run Scorer |
| Purple Cap Leader | Highest Wicket Taker |

---

## Dashboard Preview

![IPL Dashboard](images/dashboard_screenshot.png)

> Replace the image above with a screenshot of your Power BI dashboard.

---

## Project Structure
