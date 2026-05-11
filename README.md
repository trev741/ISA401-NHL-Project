# NHL Analytics and Playoff Success

---

**Course:** ISA 401 | Miami University  
**Team Number:** 9                                                  
**Authors:** Trevor Leonard, Mike Pohrte & AJ Palmer  
**Date:** May 10th, 2026  

---

### Deliverables

1. Tableau Public Dashboard: https://public.tableau.com/app/profile/trevor.leonard/viz/ISA401FinalTableau/NHLAnalyticsStoryboard-ISA401

2. Technical Presentation: https://youtu.be/eQH_RjyFNWQ

---

### Key Fields

| Field | Description |
|-------|-------------|
| `Team_Name` | The full name of the NHL teams including where they're from (ex. Anaheim) and the team name (ex. Ducks) |
| `Season` | The years in which the season took place. For example a season starting in 2017 would be 2017 - 2018 |
| `GP` | The amount of games played with shortened season in 2019 - 2020 and 2020 - 2021 |
| `Wins` | How many wins an NHL team has in a 82 game season with less games in 2019-2020 & 2020-2021. 
| `Points` | Based on 2 points for any type of win, 1 point for overtime/shootout loss and 0 for a regulation loss. |
| `Shots_For_Per_Game` | The number of shots on the opposing team per game on average that season |
| `Goals_For_Per_Game` | The number of goals scored on the opposing team per game on average that season |
| `Goals_Against_Per_Game` | The number of goals against per game on average that season |
| `Playoff_Wins` | The number of playoff wins in the postseason that year. 16 wins indicates a Stanley Cup win (18 in 2019-2020 where Tampa Bay Lightning had 2 extra wins for the play-ins |
| `Arena_Capacity` | The amount of fans allowed in the arena at maximum capacity |

---

## Instructions 

- Load the `ISA401DataFile.rmd` 
- Install all packages from `Step 0` if not already installed
- Run `Step 0`
- Run `Step 1`: You will see a CSV file named `NHL10yrFinalAdvancedStats.csv` in your files if done correctly or you can pull the csv file from the GitHub Repository
- (Can stop here if needed): For the visualizations, run the 4 R Chunks in `Step 2`

---

## Features

- **Real Life Data**: Cleaned and standard authentic data for 10 years in the NHL
- **API Extraction**: Utilized public NHL API for pulling hockey data
- **Web Scraping**: Pulled data from Wikipedia through web scraping
- **Audited Data**: We picked 20 random teams and seasons from 2014-2023 and we fact checked them through the ESPN website to ensure our data table is fully up to date

---

## Technology Stack

- **[Tableau](https://www.tableau.com/)** - Software for our visualizations
- **[GitHub](https://github.com/)** - Repository for all of our important public data

---

## Course Information

This application was developed for **ISA 401** at **Miami University** 
to help students explore and understand NHL advanced data more clearly.

---

## Data Sources

ESPN. NHL Standings | Team Standings Data
Data | https://www.espn.com/nhl/standings

NHL API. Team Summary Statistics (Regular Season & Playoffs) | 2014–2024 Seasons
Data | https://api.nhle.com/stats/rest/en/team/summary

Wikipedia. List of National Hockey League Arenas | Infrastructure Data
Data | https://en.wikipedia.org/wiki/List_of_National_Hockey_League_arenas

---


