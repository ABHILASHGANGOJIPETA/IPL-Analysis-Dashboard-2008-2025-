# 🏏 IPL Analysis Dashboard (2008–2025) | Power BI

This project is a Power BI Dashboard created to analyze Indian Premier League (IPL) data from 2008 to 2025.  
It focuses on season-wise team and player performance, helping track champions, player awards, and overall tournament insights.

---

## Dashboard Preview
Here is the IPL Analysis Dashboard built in Power BI  
![Dashboard Screenshot]()


---

## Problem Statement
The IPL produces vast amounts of data across matches, teams, and players.  
Stakeholders (teams, fans, analysts, and management) need an **interactive solution** to monitor season outcomes, player stats, and team performance trends.

---

### KPI Requirements
- **Primary KPIs**  
  - Winner team of the season (with logo)  
  - Runner-up team of the season (with logo)  

- **Secondary KPIs**  
  - Total Sixes  
  - Total Fours  
  - Total Matches Played  
  - Total Teams Participated  
  - Total Centuries  
  - Total Half-Centuries  
  - Total Venues Used  

- **Season Stats**  
  - Orange Cap – Top run scorer with runs, team, and player image  
  - Purple Cap – Top wicket-taker with wickets, team, and player image  
  - Most Fours – Player with maximum boundaries  
  - Most Sixes – Player with maximum sixes  

- **Points Table**  
  - Matches Played, Won, Lost, Tied, No Result, Total Points  

---

### Charts Requirement
- Season-wise Winners & Runner-ups (KPI Cards)  
- Batting Stats – Total Sixes, Total Fours, Centuries, Half-Centuries (Cards/Bar Charts)  
- Orange Cap & Purple Cap Holder (Dynamic Cards)  
- Most Fours & Most Sixes (Dynamic Cards)  
- Points Table (Dynamic Table with Logo, Wins, Losses, Ties, NR, Total Points)  
- Team Participation by Season (Line/Bar Chart)  
- Venues Used Over Seasons (Column Chart)  

---

## Dataset
The datasets used: **IPL_2008_2025_Data.xlsx**  

It contains information on:  
- Matches (season, date, winner, runner-up, venue)  
- Teams (team ID, team name, logo)  
- Players (runs, wickets, fours, sixes, centuries, half-centuries)  
- Points Table (wins, losses, ties, NR, points)  

---

## Data Cleaning and Preparation
Before building the dashboard, the dataset was cleaned to ensure accuracy and reliability:  
- Removed Duplicates – Eliminated repeated match records  
- Handled Missing Values – Corrected/removed nulls in player stats and match outcomes  
- Standardized Team Names – Ensured consistency across all seasons (e.g., "Delhi Daredevils" vs. "Delhi Capitals")  
- Added Player Images – Linked player stats with their images for KPIs  
- Created Date Table – Added hierarchy for season-based analysis  

---

## Tools Used
- **Power BI** (Data Visualization and Dashboarding)  
- **Excel/CSV** (Data Source and Preparation)  
- **Power Query** (Data Cleaning and Transformation)  
- **DAX** (KPI Calculations and Points Table Measures)  

---

## Key Insights
- **Chennai Super Kings and Mumbai Indians** dominated across multiple seasons  
- Player performance trends highlight consistency of Orange Cap and Purple Cap winners  
- Sixes and fours per season show the evolution of batting style over years  
- Points Table analysis reveals season competitiveness and close finishes  
- Venues used vary across seasons, reflecting IPL’s global outreach  

---

## How to Use
1. Clone this repository or download as ZIP  
2. Open the `.pbix` file in Power BI Desktop  
3. Load the dataset (`IPL_2008_2025_Data.xlsx`) if required  
4. Explore the dashboard using filters (Season, Team, Player, Venue)  

---

## Author
**Abhilash Gangojipeta**  

