# NHL 10 - Year Statistics and Playoff Success

---

**Course:** ISA 401 B | Miami University  
**Creators:** Trevor Leonard, Mike Pohrte & AJ Palmer  
**Date:** May 12, 2026  

---

### Key Fields

| Field | Description |
|-------|-------------|
| `Team_Name` | The full name of the NHL teams including where they're from (Anaheim) and the team name (Ducks) |
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


## Features

- **Real Life Data**: Cleaned and standard data for 10 years in the NHL
- **Interactive Data Table**: Sort, filter, and export results

---

## Technology Stack

- **[Tableau](https://www.tableau.com/)** - Software for our visualizations
- **[mlbplotR](https://camdenk.github.io/mlbplotR/articles/mlbplotR.html)** - R visualization for teams

---

## Course Information

This application was developed for **ISA 401** at **Miami University** 
to help students explore and understand NHL advanced data more clearly.

---

## Data Source(s)

NHL API. Team Summary Statistics (Regular Season & Playoffs) | 2014–2024 Seasons
Data | https://api.nhle.com/stats/rest/en/team/summary

Wikipedia. List of National Hockey League Arenas | Infrastructure Data
Data | https://en.wikipedia.org/wiki/List_of_National_Hockey_League_arenas

---

