# College-football-development-

College-football-development main goal is too see which college football team help to develop players to NFL.
Some teams like Alabama, Georgia, Clemson are full of 4-5 stars recruits but most of them dont make it to the first round of the NFL draft.

Otherwise, the're teams like LSU taking 2-3 stars guys like Clyde Edwards Helaire and Justin Jefferson to the first round,

Goal is to take a look at who's better developing players, which is the interest on most highschool recruits.

CFB1 is basically a scraper that get NFL draft info from pro-football-reference but iterates to get data from 2000 to 2020 with one function.
It also make some transformations because data is a mess, as expected.

Data from Highschool recruiting classes was somehow well documented, scraper was not needed.

CFB2 make some transformation on highschool recruiting classes data and tries to match "College" column from NFL Draft and Highschool data.
"Florida St will" not be the same as "Florida State"
"Boston Col." not be the same as "Boston College"
"East. Michigan" not be the same as "Eastern Michigan"

This columns needs to match in order to make counts and compare both databases.


PROJECT IS STILL ON DEVELOPMENT.

Things to do next:
-Create a script to count the number of prospects on each team from 1 to 5 stars out of highschool
-Create a script to count NFL draft picks for each team
-Creat a system to match both scripts describe above and get and overall value
