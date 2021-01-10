## Analysis of Fatal Police Shootings in US based on State wise 
# Fatal shootings between 2015 and 2020

An analysis on only shootings in which a police officer ,in the line of duty ,shoots and kills a civillian - The csv files have not tracked deaths of people in police custody,fatal shootings by off-duty officers or non-shootings deaths.

# About the data
The file fatal-police-shootings-data.csv contains data about each of the fatal shootings in csv format and I have taken data about the population in each state from worldpopulationreview.com where it contains total population 
of each race in each state .

# Observable Trends 

1. In which state the total no deaths due to police shootings was highest?

* 684 fatal shootings occurred in CA which consist of approximately 14% of all shootings. THe top 3 states in terms of total number of shootings are in California ,Texas and Florida 
![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/State.png "State vs Total Deaths")

2. What were the age group of the people shot by police in each state? 

* Most people who are shot are younger than 40's in top 4 states in terms of total number of shootings
![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/Age.png  "Age in each State vs Total Deaths")

3. Which race is affected the most in the top 4 states in terms of total number of deaths ?
* The ratio for black people (B) is clearly higher than other races. The native (N) and other (O) have very low population so a more logical comparison would be among black (B), white (W), hispanic (H), and asian (A) races.The ratio of deaths_per_million for black(B) people is double the ratio . The diffrence between black(B) and White(W) people are even more.
 ![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/StatevsRace.png "Racial Deaths per State")
 * If we consider the race of people involved to total population of their race in each state Asians are shot the most in the state of Florida 
  ![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/RaceineachState.png  "Race in each State vs Total Deaths")
  
 4. Is there any continuous upward or downward trend in the daily number of shootings from 2015 to 2020
 * Although there is a peak we cannot observe any continuous trend
   ![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/10dayave.png  "10 Day Average")

# Summary

I used python data analysis ,visualization libraries and gmaps to analyze and visualize police shootings based on State. Used Gmaps to represent the total people shot by police in each city 
![alt text](https://github.com/EvanK215/ProjectOnePolice/blob/RJbranch/Images/Totalkillingsineachcity.png "Total people shot in each city")
