# Home vs Away Analysis for Premier League 23/24
This repository contains a Jupyter Notebook analyzing home and away performance in the English Premier League for the 2023 season. The analysis focuses on comparing average points per game for each team at home and away, visualized through interactive and static plots.

## Data
The data used in this analysis is sourced from the soccerdata library, specifically the MatchHistory class.

## Dependencies
soccerdata
scipy
matplotlib
pandas
seaborn
plotly

## Key Findings
Data visualization is crucial for understanding insights. I used Plotly to create an interactive line graph showcasing the average points per game for each team at home and away. The interactive plot can be found [here](https://damianwong01.github.io/epl_home_away_analysis_23-24/interactive_plot.html).

### Facet Grid with Seaborn
For a more granular perspective, I created a facet grid using Seaborn. This displays individual point plots for each team, visually representing their average points per game at home and away.

### Statistical Significance: T-test for Home Advantage
To determine if the observed differences in average points per game are statistically significant, we conduct a paired t-test. This test assumes the same teams play both home and away games, making their performances directly comparable.

The code utilizes scipy.stats to perform the t-test and interpret the results.

### Interpretation and Next Steps
The paired t-test confirms a statistically significant home advantage in the Premier League. However, this is just the beginning. Future research could explore:
- Factors influencing home advantage, such as crowd size, travel distance, team tactics, and player performance.
- Variations in home advantage across different teams and over time.

## License
This project is licensed under the MIT License.
