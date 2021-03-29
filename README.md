# Prediktaa

Springboot application that would expose REST end points which can be used by a front end system that exposes the Predikta application, which would be deployed to Cloud.

**Pages required:**

User / Admin page: 

A user should be able to select a date via a Calender object. 
A REST end point accepts the date as an input and returns the number of matches on the date as 'Match 1' and 'Match 2' and also the teams playing on that date and also the players belonging to both teams.
The first drop down lists the number of matches to be played in a day, and lets the user choose which match he wants to make a prediction for (Match 1, Match 2)
Based on the match number selected in the first drop down, the second drop down is populated with the two team names, and the subsequent three drop downs are populated with the player names of these two teams. 
After making predictions for all matches on the date selected, the data is saved
The user should be allowed to update his prediction till the match starts

