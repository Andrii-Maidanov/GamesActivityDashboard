# Games Activity Visualization in Tableau Public

## Overview

This project involves creating visualizations in Tableau Public to analyze user activity data in games. The dataset includes information about users' activities, the time spent in different game activities, and demographic details. The visualizations help to understand user engagement, average playtime, and trends across different age groups and time periods.

## Tasks

### 1. Monthly User Metrics
- Create a sheet that displays the total number of users and the percentage of users engaged in "Battle pass" activities monthly.
- The sheet should include two metrics:
  - Total number of game users.
  - Percentage of total users who spent any amount of time in activities related to "Battle pass."
- **Tip**: Activity types can be found in the `game_activity_name` field.

### 2. Average Play Time Per Player
- Create a sheet that displays the average playtime per player on a monthly basis.
- Add a label that shows the average playtime per player in hours and minutes, formatted as "HH:MM."
  - The minutes should always be displayed as two digits (e.g., 00:02, 21:07, 05:53).

### 3. Heatmap of Play Time by Age Group and Quarter
- Create a heatmap that shows the average playtime by age group (in 5-year increments) and by quarter.
- Example age groups: "10-14", "15-19", ..., "80-84".

### 4. Dashboard Creation
- Combine all three sheets into a single dashboard.
- Add filters to the dashboard for:
  - Activity date.
  - Age group.
  - Game name (found in the `game_activity_name` field).
  - Device language.

## Visualization Example

You can view the completed dashboard on Tableau Public using the following link: https://public.tableau.com/app/profile/andrii.maidanov/viz/GAMESACTIVITIES/Dashboard2

[Games Activity Dashboard](https://public.tableau.com/views/Games_Activity_Viz/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Tools Used
- Tableau Public
- CSV file with user activity data

