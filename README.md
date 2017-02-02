# Data-Visualization-D3-JavaScript
Data Visualization with D3.js and Dimple.js

Summary - 
The baseball data is a subset of Lahman's Baseball Database which contains statistics for Major League Baseball from 1871 through 2014.
This explanatory data visualization shows how BMI and handedness affect batting statistics.
After analyzing the visualization we can see that left handed hitters, and hitters with higher BMI, tend to have a higher batting average and number of home runs.
Interestingly we can see that switch hitters have the highest batting average but the lowest average number of home runs.

Design - 
I decided to use grouped averages because I felt that scatter plot of all of the individual player was both distracting and provided little insight.
After getting feedback from friend 'A' I grouped the variables height and weight together as BMI as this would give a better understanding of the player's body type.
I also decided to keep the original average on the graph so it could be used as a comparison (From Friend 'B').
Initially I was going to toggle that stats on the Y-axis but friend 'C' advised me to put the other stat on the x-axis and use colors to distinguish facets. 

Feedback - 
- maintain original averages
- use BMI instead of weight and height
- proper labels on the axes
- use the x and y axis for stats as opposed to using the x axis for categories
Post Udacity Review:
- increased font sizes for the legend and axes
- added a more decriptive title
- improved tooltip descriptions. As an example I changes "sqrtTotalPlayers" to "Relative Size (Total)"
- increased the size of the overall visualization

Resources - 
dimplejs.org
stackexchange
w3schools