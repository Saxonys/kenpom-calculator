# Kenpom Team Simulator

This is a simple web-based simulation tool that uses KenPom dataset values to simulate basketball games between two teams. It allows users to choose a home team and away team from a KenPom CSV dataset, input a neutral site preference, and view projected scores and win percentages based on KenPom data.

# Why did I make this?

This was made as apart of my AP Computer Principles exam back in high school. This was my first project in javascript.

# How it works

### CSV File
  * The user uploads a CSV file containing KenPom data that includes team statistics like adjusted offense, adjusted defense, and pace.
  * The data will be parsed, and dropdown lists for selecting home and away teams are populated.

### Team Selection
  * Users can select their home team and away team from the dropdown lists.
  * Users can choose if the game is played on a neutral site (no home-court advantage) or not.

### Simulation
  * The simulation is run using the selected teams and neutral site option.
  * The adjusted offensive, defensive, and tempo values from the KenPom dataset are used to project the score for both teams.
  * The win probability is calculated for both teams based on their ratings.

### Results
  * The projected score for both teams is displayed, as well as their respective win percentages.

I've left a kenpom CSV file for you to test on. Those Kenpom NET rankings are from January of 2023, and can be replaced with the latest rankings at https://kenpom.com/ .
