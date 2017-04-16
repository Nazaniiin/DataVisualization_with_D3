# Explanatory Data Visualization Using D3

## Summary

In this project I analyze a dataset on performance of baseball players based on their `Height`, `Weight` and `Handedness`. I observe how these factors can affect the number of [Home Runs(HR)](https://en.wikipedia.org/wiki/Home_run) and [Batting Average(BA)](https://en.wikipedia.org/wiki/Batting_average) a player can have. 

I create two plots, one showing the relationship between `Height`, `Batting Average(BA)`, and `Home Runs(HR)`; another one showing the relationship between `Weight`, `Home Runs(HR)`, and `Handedness`. 

## Design 

To create a useful visualization that can help my audience understand the relationship, I tried to use simple elements and colors to avoid confusion. An informative visualization can be simple and at the same time transfer the message I intend to share with my audience quickly. 

Since for each player their height, weight, and handedness are provided in the dataset, I wanted to make use of all these variables in drawing my conclusions depending on whether I can find any patterns.

### Plot 1: How does the height of a player affect the Batting Average(BA) score? How does it relate to the Home Runs(HR)?

In this plot, I first drew a 2 dimension plot, displaying `height` against `batting average(BA)`. I grouped the data by height and I could immediately see a negative correlation between these two variables. As the height of players increased, their batting average (BA) intended to drop. 

I decided to add `home runs(HR)` to the same visualization to observe the relationship with `height`:
- The number of home runs (HR) seemed to have been more stable for those who were 70-75 inch tall
- There seems to be a sudden rise in the number of home runs (HR) for those who were 65-inch tall. Those players also have the highest number of batting average(BA) amongst the rest of the players.

### Plot 2: How does the weight of a player affect the number of Home Runs(HR)? Does handedness play a role in here as well?

In my second plot, I decided to observe how weight can/might affect the number of home runs(HR). I also decided to add the `handedness` variable to see how weight and handedness are related.

Based on this plot, I saw a positive correlation between weight of players and the number of home runs(HR) they scored:
- As the weight of a player increases, the number of the home runs(HR) increases as well
- There also seems to be a trend for higher number of home runs(HR) among left-handed players

## Feedback 

include all feedback you received from others on your visualization from the first sketch to the final visualization

## Information on the Dataset

This dataset contains 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs.

I use this dataset to create visualizations that show differences among the performance of the baseball players.

## Resources 

- https://bost.ocks.org/mike/selection/
- https://blog.decayingcode.com/post/Easy-Charting-in-JavaScript-with-d3js-and-Dimple-from-CSV-data/
- https://gist.github.com/rgilredondo/4580cf3269e5461efb866d47a6e94c4c
- https://gist.github.com/Amoozegar/b48cfdb57b52174a3c71fba0998f0258
- https://www.sitepoint.com/create-data-visualizations-javascript-dimple-d3/
- https://bost.ocks.org/mike/bar/
