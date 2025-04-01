# Rockies_Game_Dashboard  
Final project for 2020 Sports Statistics course at the University of Denver using R.
Code and Dashboard created by Cassy Miller  

<img src = "https://pngimg.com/uploads/at_sign/small/at_sign_PNG86.png" alt = "emaillogo" width = 20> [Email](mailto:cassydmiller@yahoo.com) 
<img src = "https://cdn-icons-png.flaticon.com/512/25/25231.png" alt = "gitlogo" width = 20> [GitHub](https://github.com/cassydm) 
<img src = "https://images.icon-icons.com/2428/PNG/512/linkedin_black_logo_icon_147114.png" alt = "linkedinlogo" width = 20> [Linkedin](https://www.linkedin.com/in/cassydm/)

## [Dashboard](file:///C:/Users/cassy/OneDrive/Documents/DU/Junior%20Year/Spring%202020/Sports%20Amalytics/Rockies%20Project/Rockies-Dash-Final.html)  

The R code for the dashboard can be found in "Rockies Final Report.rmd", and the html is stored in "Rockies-Final-Report.html" in the docs folder.  

**[View dashboard here](file:///C:/Users/cassy/OneDrive/Documents/DU/Junior%20Year/Spring%202020/Sports%20Amalytics/Rockies%20Project/Rockies-Dash-Final.html)**  

## About  

This goal of this project was to create a dashboard for the Colorado Rockies analytics team to use in order to quickly analyze game statistics and review player performance. 

Data was scraped from [Baseball Reference](https://www.baseball-reference.com/).  

## [Dashboard](file:///C:/Users/cassy/OneDrive/Documents/DU/Junior%20Year/Spring%202020/Sports%20Amalytics/Rockies%20Project/Rockies-Dash-Final.html) Overview  

> This game details various statistics from the Colorado Rockies v Toronto Blue Jays game played 5/31/2019.  

### Basic Game Info

This section includes *game info*, *Batters Box Score*, and *OBP and BA*. 

Game Info  
> Game info includes Date, Start Time, Location, Temperature, Weather Conditions, Wind, Attendance and Final Score  

Batters Box Score  
> Includes every batter for both TOR and COL, their position, at bats, runs, hits, and Runs batted in.  

OBP and BA  
> Includes a chart showing the comparision of OBP (x-axis) to BA (y-axis).  

> Each point represents a player, and hovering over the point gives exact details.  

> This chart is used to show how higher OBP correlated to highter BA, and how the Rockies out performed the Blue Jays to secure their win.  

### Spraycharts  

This section highlights each Rockies batter's hits during the game (right), comparing it to their performance over the 2019 season (left)  

### Batter's Boxes  

This section shows the location of pitches the Rockies batters faced for the TOR game (right) v the location of pitches for the 2019 season (left). The chart also shows what pitches were swung at.  

### Pitches the Rockies Batters Faced  

The charts in this section detail the pitch type, and their frequency for the TOR Game.  

> The chart on the left shows Pitch Type on the x-axis and their frequency on the y-axis. The bars are broken up by Rockies batters to show what pitches targeted which batters. For instance, very few batters faced a Curveball (CU), while most batters saw a Slider (SL) thrown.  

> The chart on the right shows the breakdown by pitchers in the game. This section shows that only Edwin Jackson (TOR Pitcher) threw Cutters (FC) and Two Seam Fastball (FT), which can provide useful information in future scenarios.  

### What did the Rockies Swing at?

This section shows each Rockies Batter and the pitch types they swung at during the TOR game (left). The right chart shows the location of pitches swung at by batter, and hovering over the point details the pitch type and hit type (null if strike), as well as the outcome.  

### Hit Distance  

There are two sub-sections in this section: *Hit Distance & Launch Speed* and *Hit Distance & Launch Angle.  

Hit Distance v Launch Speed  

> The charts show launch speed (x-axis) v the distance the ball traveled. Left shows 2019 season while right shows the TOR game. Each point can be hovered over to detail the pitch type and outcome during the game.  

> The purpose of this report is to show how the relationship between the launch speed of a ball and interestingly how a lot of deep balls result in fly ball out if not hit with a high enough launch speed.  

Hit Distance v Launch Angle  

> Similarly, this section is the same as the previous, but uses launch angle on the x-axis instead.  

### Rockies Pitching Info  

This secion includes four subsections.  

2019 Season Pitches  

> Shows German Marquez (Rockies Pitcher) and his 2019 pitch distribution by type.  

Pitches for Game May 31, 2019 v TOR  

> Shows German Marquez' pitches for the TOR game by type and frequency. 

2019 Season Release Speed  

> Shows German Marquez' release speed by pitch type.  

May 31, 2019 Release Speed  

> Shows German Marquez' release speed by pitch type for the TOR game.  

### Pitching Accuracy  

This section shows each pitch and their thrown location for Marquez' 2019 season (left) vs the TOR game (right), as well as the outcome: either ball (B), strike (S), or hit (X).  

### Standings as of May 31, 2019  

Team standings for each team (COL and TOR).  

> COL is in the National League (NL) West.  
> TOR is in the American League (AL) East.  

