# IPL-Project
# IPL 2022 Capstone Project

Exploratory data analysis of IPL 2022 match data using Python. The notebook covers team performance, toss trends, key player performances, and venue analysis, with visualizations for each.

## Contents

- `IPL_Project_.ipynb` – the full analysis notebook

## Analysis Overview

**Basic exploration**
- Dataset shape, data types, and null-value check

**Match and team insights**
- Team with the most match wins
- Toss decision trends (bat vs. field)
- Toss winner vs. match winner (percentage of matches where the toss winner also won)
- How teams win: by runs vs. by wickets

**Key player performances**
- Most "Player of the Match" awards
- Top two run scorers
- Top 10 best bowling figures

**Venue analysis**
- Number of matches played at each venue

**Custom questions**
- Highest winning margin by runs
- Highest individual score
- Best bowling figure

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## How to Run

1. Install the dependencies:
   ```
   pip install numpy pandas matplotlib seaborn jupyter
   ```
2. Place the IPL dataset (`IPL.csv`) on your machine and update the file path in the first cell of the notebook:
   ```python
   df = pd.read_csv("path/to/IPL.csv")
   ```
3. Open the notebook and run all cells:
   ```
   jupyter notebook IPL_Project_.ipynb
   ```

## Dataset Columns Used

`match_id`, `match_winner`, `toss_winner`, `toss_decision`, `won_by`, `margin`, `player_of_the_match`, `top_scorer`, `highscore`, `best_bowling`, `best_bowling_figure`, `venue`

## Author
- Arpita Singh
