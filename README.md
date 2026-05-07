---
Course: ISA 401

---

# Project Name: The NHL Economic Analytics
### Course: ISA 401 B
### Creators: Trevor Leonard, Mike Pohrte
### Date: 05/12/26

### Key Fields

| Field | Description |
|-------|-------------|
| `Season` | The years in which the season took place. For example a season starting in 2012 would be `2012-2013` |
| `Economic_Era` | The era in which the season was played. This includes either `Pre-Cap` or `Salary cap` |
| `Team_Name` | The full name of the NHL teams including where they're from (Anaheim) and the team name (Ducks) |
| `Season_Rank` | Out of x NHL teams, where did they rank in terms of overall points with 1 being the best. |
| `Wins` | How many wins an NHL team has in a 82 game season with less in 2004-2005*, 2012-2013, 2019-2020 & 2020-2021. |
| `Points` | Based on 2 points for any type of win, 1 point for overtime/shootout loss and 0 for a regulation loss. |
| `Playoff_Wins` | How many wins a team had in the playoffs. 16 wins indicates a Stanley Cup win. |
| `League_Cap_Ceiling_Millions` | The maximum a team is allowed to spend on players and goalies |
| `Team_Spend_Millions` | The amount an NHL team spent that year on cap space in millions. |
| `Forward_Cap_Pct` | The percentage (%) of the `Team_Spend_Millions` that is spent on forwards |
| `Defense_Cap_Pct` | The percentage (%) of the `Team_Spend_Millions` that is spent on defense |
| `Goalie_Cap_Pct` | The percentage (%) of the `Team_Spend_Millions` that is spent on goalies |
| `Forward_Spend_Millions` | The total spending for that of forwards (LW, C and RW) in millions |
| `Defense_Spend_Millions` | The total spending for that of defense (LD and RD) in millions |
| `Goalie_Spend_Millions` | The total spending for that of goaltenders (G) in millions |
| `Cost_Per_Point` | How much each million spent costs to get a point in a given season |

---


## Features

- **Real Life Data**: Cleaned and standard data for 25 years in the NHL
- **Interactive Data Table**: Sort, filter, and export results

---

## Technology Stack

- **[Tableau](https://www.tableau.com/)** - Software for our visualizations
- **[mlbplotR](https://camdenk.github.io/mlbplotR/articles/mlbplotR.html)** - R visualization for teams

---

## Course Information

This application was developed for **ISA 401** at **Miami University** 
to help students explore and understand NHL economic data more clearly.

---

## Data Source(s)

NHL API. Team Summary Statistics (Regular Season & Playoffs) | 1999–2025 Seasons
Data | https://api.nhle.com/stats/rest/en/team/summary

PuckPedia. Historical NHL Salary Cap Ceilings | 2005–2025 Seasons
Data | https://puckpedia.com/

Wikipedia. List of National Hockey League Arenas | May 6th, 2026 Snapshot
Data | https://en.wikipedia.org/wiki/List_of_National_Hockey_League_arenas

---

