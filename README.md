# FIFA World Cup Data Analysis Dashboard

**Project Title:** FIFA World Cup Data Analysis Dashboard

## Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Dashboard Screenshot](#dashboard-screenshot)
4. [Metadata](#metadata)
    - [Excel File: `world_cup_results.xlsx`](#excel-file-world_cup_resultsxlsx)
    - [Sheet 1: `WorldCupMatches`](#1-sheet-name-worldcupmatches)
    - [Sheet 2: `WorldCupResults`](#2-sheet-name-worldcupresults)
    - [Sheet 3: `WorldCups`](#3-sheet-name-worldcups)
    - [Usage Notes](#usage-notes)
5. [Data Source](#data-source)
6. [File Structure](#file-structure)
7. [How to Use](#how-to-use)
8. [Contact](#contact)
9. [Author](#author)

## Overview

This project provides a comprehensive analysis of FIFA World Cup data spanning from 1930 to 2014. The dashboard visualizes key metrics, including attendance by country, tournament appearances, statistics by year, and the distribution of World Cup champions. The analysis was conducted using data visualization techniques in Power BI to uncover insights into the historical performance and trends of the World Cup.

### Key Features:
- **Attendance by Country:** Visualizes the global participation in World Cup events by mapping the attendance of various countries.
- **Tournament Appearances:** Highlights the countries with the most World Cup appearances, providing insights into consistent performers.
- **Tournament Stats by Year:** Analyzes goals scored, matches played, and the number of qualified teams over the years.
- **Tournament Champions:** Displays the distribution of World Cup wins among different nations using a donut chart.
- **Number of Tournaments Hosted:** Shows which countries have hosted the World Cup and how many times, indicating the global spread of the tournament.

## Dashboard Screenshot

![FIFA World Cup Dashboard](/assets/images/dashboard_overview.png)

*Above is a screenshot of the FIFA World Cup Data Analysis Dashboard, showcasing the visualizations and insights derived from the data.*

## Metadata

### Excel File: `world_cup_results.xlsx`

This Excel file contains three sheets with comprehensive data on FIFA World Cup matches, results, and tournament details. Below is the metadata for each sheet.

---

#### 1. **Sheet Name:** `WorldCupMatches`

**Description:**  
This sheet contains detailed records of individual World Cup matches, including information on the date, teams involved, match results, and the stadium where the match was played.

**Columns:**
- `Year` (integer): The year the World Cup took place.
- `Datetime` (datetime): The date and time the match was played.
- `Stage` (string): The stage of the tournament (e.g., Group, Quarter-final).
- `Stadium` (string): The name of the stadium where the match was held.
- `City` (string): The city where the match was played.
- `HomeTeamName` (string): The name of the home team.
- `HomeTeamGoals` (integer): The number of goals scored by the home team.
- `AwayTeamGoals` (integer): The number of goals scored by the away team.
- `AwayTeamName` (string): The name of the away team.
- `Attendance` (integer): The number of spectators attending the match.
- `Referee` (string): The name of the match referee.
- `Assistant1` (string): Name of the first assistant referee.
- `Assistant2` (string): Name of the second assistant referee.
- `RoundID` (integer): Identifier for the round of the match.
- `MatchID` (integer): Unique identifier for the match.
- `Home Team Initials` (string): Initials of the home team.
- `Away Team Initials` (string): Initials of the away team.

---

#### 2. **Sheet Name:** `WorldCupResults`

**Description:**  
This sheet summarizes the results of the World Cup tournaments, including the winners, runners-up, and final scores of the deciding matches.

**Columns:**
- `Year` (integer): The year the World Cup took place.
- `Country` (string): The host country of the World Cup.
- `Winner` (string): The country that won the World Cup.
- `Runners-Up` (string): The country that was the runner-up.
- `Third` (string): The country that secured third place.
- `Fourth` (string): The country that secured fourth place.
- `GoalsScored` (integer): Total goals scored during the tournament.
- `QualifiedTeams` (integer): The number of teams that qualified for the tournament.
- `MatchesPlayed` (integer): Total number of matches played.
- `Attendance` (integer): Total attendance across all matches in the tournament.

---

#### 3. **Sheet Name:** `WorldCups`

**Description:**  
This sheet provides detailed information on each World Cup tournament, including the host countries, the number of matches played, goals scored, and total attendance.

**Columns:**
- `Year` (integer): The year the World Cup took place.
- `Country` (string): The host country of the World Cup.
- `Winner` (string): The country that won the World Cup.
- `Runners-Up` (string): The country that was the runner-up.
- `Third` (string): The country that secured third place.
- `Fourth` (string): The country that secured fourth place.
- `GoalsScored` (integer): Total goals scored during the tournament.
- `QualifiedTeams` (integer): The number of teams that qualified for the tournament.
- `MatchesPlayed` (integer): Total number of matches played.
- `Attendance` (integer): Total attendance across all matches in the tournament.

---

### Usage Notes:
- **Date Formatting:** Ensure that the `Datetime` column in the `WorldCupMatches` sheet is correctly formatted when performing time-series analyses.
- **Missing Values:** Some columns may have missing values, especially in earlier years where historical data may be incomplete.

## Data Source

The data used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/abecklas/fifa-world-cup/data). The dataset includes historical records of World Cup matches, attendance, and team performance metrics.

### File Structure:
- **/dashboard_fifa_wc_analysis/**: Contains the Power BI dashboard file.
- **/images/**: Contains images used in this repository (e.g. logos, screenshots).
- **README.md**: This file, providing an overview of the project.

## How to Use

1. **Download the Dashboard:** Clone or download this repository to your local machine.
2. **Open in Power BI:** Open the `.pbix` file in Power BI to explore the data and visuals.
3. **Explore the Data:** Use the filters and interactive features to gain insights into World Cup performance metrics.

## Contact

For any questions or feedback, please contact [Eshwanth](mailto:eshwanthj@gmail.com).

## Author
_Eshwanth_
