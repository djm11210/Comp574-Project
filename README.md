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

t

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
## The Source code is available here [Comp 574 Project Source Code](https://github.com/djm11210/Comp574-Project/blob/main/Comp574Project.ipynb)

### Determine appropriate measures of central tendency (Mean, Mode, and Median ) and dispersion for at least three selected variables, including one quantitative variable (column) and one qualitative variable (column). For a quantitative variable, select at least one measure of central tendency and at least one measure of variance ( Sample Standard Deviation or Variance). For the qualitative variable, select one measure of central tendency.
1. I think the appropiate measurement is mean because all of the questions i want to answer relate to the average
2. qualitative variable  would be the stats column and it would be Sample Standard Deviation.
3. quantitative variable would be the height column and it would be Sample Standard Deviation.


### Describe at least two questions that your analysis is meant to answer, and describe how these questions are answered
1. average height in each postion in the 2019 season how I would answer this question I would use df.loc to specify what column and row would I need. For the column it would be the 2019 season of the nba  and the row would be all the nba players that were in the league in 2019 and with that row I will be able to go though all of the players in the 2019 season and select the weight vaule of all of the players in the 2019 season and then I will select the players in each postion and that will show me all the players in the spefic postion along with all of there weight then i can use the mean() build in function and that will answer my question.that will answer my question.
2. average salary for each postion in the 2019 season I would answer this question I would use df.loc to specify what column and row would I need. For the column it would be the 2019 season of the nba  and the row would all of the nba players salarys in the 2019 season. and with that row I will be able to go though all of the players in the 2019 season and select the salary vaule of all of the players in the 2019 season and then I will select the players in each postion and that will show me all the players in the spefic postion along with all of there salary then i can use the mean() build in function and that will answer my question.

### Describe at least two more questions that your analysis is meant to answer using graphs. You should include at least two graphs of different kinds (e.g., pie chart, bar chart, histogram, box plots, etc.) to support your answer to these two questions. Explain the purpose of each graph and indicate what particular features are worth pointing out?

1.best stats in each postion in the 2019 season I think this question would best be answered with a bar graph because it will display each of the 5 postions in basketball and what is the best stats in each postion. Bar graphs I think fits the best because there are muiple stats in the NBA some examples are 
PTS: points
FGM, FGA, FG%: field goals made, attempted and percentage
FTM, FTA, FT%: free throws made, attempted and percentage
3FGM, 3FGA, 3FG%: three-point field goals made, attempted and percentage
REB, OREB, DREB: rebounds, offensive rebounds, defensive rebounds
so with all of these diffent stats I think the bar graph will display all of the stats the best out of other graphs

2.average weight for each postion in the 2019 season  I think the best graph to answer this question would be a pie chart the reason why I think this is the best graph for this question is because there are only 5 postions in basketball center, power forward, small forward, point guard, and shooting guard. And we are only finding the average weight I think a pie chart would be the simplest and cleanest to show the data because we only need to find one vaule for each postion so theres only 5 vaules for the graph and I think a pie chart would show it off the best.

### Demonstrate with at least one example how to use groupby and/or merge operations using the Pandas library.
