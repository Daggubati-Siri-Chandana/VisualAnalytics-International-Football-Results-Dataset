# VisualAnalytics-International-Football-Results-Dataset

Performed data analysis on International football results data set collected from 30th Nov 1872 to 19th Nov 2019. We can use any analyzing or visualization techniques as per the requirement. | [Data](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017) |


### Win prediction based on history of victories
<p align="justify">The motivation behind this task is to predict the results of the game played among different countries based on the historical victory ratios of each country team. 
To perform this visualization we calculate the home-wins, away-wins and total-victory ratio. Then the top 16 teams are selected from the resulted data. We then randomly group these 16 team for a match between two teams based on the group of 2 created. Further, based on the total-victory ratio the winning team is predicted from each group. In the next set we have 8 teams for tournament. This process is iterated till final winning team is predicted. To visualize this layer wise node link diagram is used.</p>

<p align="center"><img src="https://github.com/Daggubati-Siri-Chandana/VisualAnalytics-International-Football-Results-Dataset/blob/master/Images/fig9.png"></p>

By performing this plot we can predict the winning team based on their victories in the past. The plot below shows one such arrangement of win prediction based on one of the grouping possibilities for top 16 teams.


### Predicting winning rate/losing rate
<p align="justify">The motivation behind this task is to guess how probably a team wins/loses if it is the home team or away team or irrespective of teams. We Calculate the result of teams based on home score and away score if it (#wins, #draws, #losses). Now aggregate based on home teams/away team, then get win count and loss count and divide it by total count to get the percentage.We plot the obtained percentage values of the home team, away team, or both using choropleth map in plotly.</p>

<img src="https://github.com/Daggubati-Siri-Chandana/VisualAnalytics-International-Football-Results-Dataset/blob/master/Images/Screenshot%202019-11-24%20at%2010.52.51%20PM.png" width="500">  <img src="https://github.com/Daggubati-Siri-Chandana/VisualAnalytics-International-Football-Results-Dataset/blob/master/Images/Screenshot%202019-11-24%20at%2010.55.00%20PM.png" width="500">

### Favorability of teams
<p align="justify">The motivation behind this task is when a team wants to know about its rival team based on previous histories of matches of the rival team with other teams, we will plot the Favorability of the team's winning/losing the match with the other teams.We visualize the Favorability of country using choropleth map in a range of values 1, 0, and -1 on a color scale of green, white, and red, respectively. If there is no match with that country team, it is colored black.</p>

![](https://github.com/Daggubati-Siri-Chandana/VisualAnalytics-International-Football-Results-Dataset/blob/master/Images/Screenshot%202019-11-24%20at%209.49.13%20PM.png)
