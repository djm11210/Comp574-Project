# Comp574-Project
Comp 574 Project

### Project Milestone 1



## The data is collected through the [balldontlie API](https://www.balldontlie.io/#introduction)


### What is the data and what information is in each column

1. there is a stats column that stores the stats of the NBA season
2. there is a players column that stores all of the players In that NBA season
3. there is a specific player column that stores all of information of a NBA player
4. there is a team column that stores all of the NBA teams in the league
5. there is a specific team column that stores all of information of a NBA Team
6. there is a games column that stores all of the NBA games in a specific season
7. there is a specific game column that stores all of the games information
8. there is a season averages column that stores the season averages in a nba season



### Questions I want to answer with this project

1. best stats in each postion in the 2019 season
2. average stats for each position in the 2019 season
3. average height in each postion in the 2019 season
4. average weight for each postion in the 2019 season
5. average salary for each postion in the 2019 season

## The Source code is available here [Comp 574 Project Source Code](https://github.com/djm11210/Comp574-Project/blob/main/Comp574Project.ipynb)

### The dataset file in CSV format [Dataset CSV file ](https://github.com/djm11210/Comp574-Project/blob/main/data.csv)



### Project Milestone 2

### The local notebook should connect to your data stored either in GCP BigQuery or in a GCP storage bucket. Your code should not read from local data files.

### Determine appropriate measures of central tendency (Mean, Mode, and Median ) and dispersion for at least three selected variables, including one quantitative variable (column) and one qualitative variable (column). For a quantitative variable, select at least one measure of central tendency and at least one measure of variance ( Sample Standard Deviation or Variance). For the qualitative variable, select one measure of central tendency.

### Describe at least two questions that your analysis is meant to answer, and describe how these questions are answered
1. average height in each postion in the 2019 season how I would answer this question I would use df.loc to specify what column and row would I need. For the column it would be the 2019 season of the nba  and the row would be all the nba players that were in the league in 2019
2. average salary for each postion in the 2019 season I would answer this question I would use df.loc to specify what column and row would I need. For the column it would be the 2019 season of the nba  and the row would all of the nba players salarys in the 2019 season.

### Describe at least two more questions that your analysis is meant to answer using graphs. You should include at least two graphs of different kinds (e.g., pie chart, bar chart, histogram, box plots, etc.) to support your answer to these two questions. Explain the purpose of each graph and indicate what particular features are worth pointing out?
1.best stats in each postion in the 2019 season
2.average weight for each postion in the 2019 season

### Demonstrate with at least one example how to use groupby and/or merge operations using the Pandas library.
