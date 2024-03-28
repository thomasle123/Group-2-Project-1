# Group-2-Project-1

**Team Name**
Sp24_61608_Group 2 

**Team Members:**
Dylan Artis (https://github.com/DJA706)
Dana Baus (https://github.com/Dananasplitt)
Molly Butkovich (https://github.com/mollybutkovich)
Connor Coniglio (me)
Thomas Le (https://github.com/thomasle123)
Alex Quinlan (https://github.com/AlexQuinlan12)

**Problem Description:**
A description of the client scenario that you are modeling describing it in sufficient detail that
makes sense in the context of your data model. This should be reflective of your conversation
with your client.
**Our response:** 
In our interactions with our client (Atlanta Braves Management), we have decided to make a comprehensive system to manage the teams operations using a relational database model in SQL. In this model, we created many entities that break down the structure of the Atlanta Braves organization. As seen in our model, we have highlighted many key sectors of our client's organizations that require the most focus. For the Atlanta Braves’ organization to be successful and optimize its efficiency and profitability, the management team needs to use these highlighted components to make the right decisions. 

By using our relational database on your baseball operations, our client will be able to see a 360-degree view of the team’s current operations and use that to assess your current strengths and weaknesses. From this assessment, the Braves’ management team will be able to derive key insights and metrics on aspects of their business that they otherwise might have been unaware of. Utilizing this, we are sure that they will make key changes that will thrust the company in the right direction.

Our model and analysis were created to ensure proper integration of all aspects of team management. Due to the dynamic nature of the MLB and the Atlanta Braves position in it, this breakdown of our client’s structure will highlight the organization’s operational needs and allow the company to gain a competitive advantage amongst other teams.

**Our Data Model:**
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/bd288337-f0d9-4fad-aada-b4fcc5ab9587)


**Data Dictionary:**
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/a24170ae-f1de-43df-81f3-e4d2fb2b336a)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/dbb83533-eff6-4a1a-a0d3-6be9fb00ebf2)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/34b0a113-fc98-4aef-a641-7ecf8d0b840f)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/67f863ce-a0b7-44f1-ba72-eb2626c21965)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/9c2fc2b2-ab81-4639-af3e-7cd19398e400)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/8bb477d6-491c-4d61-81e7-e34983e73c7b)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/5ff033fb-3d68-4ecd-990d-5905c3b1d281)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/208fe698-4e23-4cbd-913b-9d354e3c2cab)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/4dfa8519-31d9-489e-9eb5-dd0eac72161f)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/3b4bbfcf-0e22-48ec-8ce7-262569788db5)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/4ca5c3b3-210d-4b4c-9ff5-1bf3d27a67dd)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/12165e9d-7815-48f4-a1a4-c9ce37fca596)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/52253923-ce33-4771-b26c-fffa3f27d2b9)
![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/c6498037-adf4-4fd6-966c-81b86e93deb7)

**Queries:**

![image](https://github.com/ConnorConiglio/Group-2-Project-1/assets/163012186/c9d27f2b-1a37-4bf3-b611-2efdee3d12b3)

#1. List the first name and last name of the players who were not injured last season (assuming no one was injured this season). 

Description: This query would be used by coaches to determine which players need to be watched more closely to prevent  recurring injuries. This query returns player names who had an injury in the previous season. Our client could use this information to monitor rehabilitation health for injury-prone players and make informed decisions on player usage rate (i.e. - don't play injury-prone players too much every game and give them more time for rehabilitation to preserve them throughout the season).

#2. List the names of all coaches, their roles, and the date of the practices they attend. Order the practice dates chronologically. 

Description: This query will result in showing which practices coaches are involved in and what their role is. This query would be used to develop coach schedules and potentially weed out errors. This query is especially useful for team managers or owners who want to have available coaches for press conferences or meetings outside of practice. As a result of our client using this, they can maximize coach efficiency and make sure players are getting optimal instructions from all the coaches they need it from.

#3.List out player name, contract salary and endDate for all players whose strength on their scouting report is pitching

Description: The query will print player names, their salary, and the end date of their current contract for players with the scouting strength pitching. This query is useful to coaches and team owners who want to evaluate player’s performance and compare their initial scouting strengths to current performance. They can also use this information when making new contracts and potentially give raises to players with high-performance metrics.

#4. Count the number of equipment items where the type is a bat and the item is broken. 

Description: The purpose of this query is to provide a count of how many bats are broken. This query is useful to coaches so they know how many bats need to be replaced and the amount of players who need new equipment. They can use the query to determine how many new bats need to be ordered. By doing this, our client will be able to ensure players have their needed equipment and it will allow for maximum practice and player improvement efficiency.

#5. List the gameID, score of the opponent with the opponent name, and the score of the Braves for every game the braves won in the 2023 season.

Description: Query 5 is useful to players and coaches, informing them of the games where they performed well. They can use the information from the query to determine factors that contributed to their success and try to replicate these conditions in future games. It does this by filtering and aggregating the team's scores vs the opponent's scores to highlight their success.

#6. List players names, their types of injuries, and the doctor that treats them. Do this for players who have scored more than one run in a game.

Description: This query outputs players who have scored more than one run in a game; returning their name, type of injuries, and doctor name. It groups the results by player name, injury type, and doctor name. The point of using this query would be to track how players are performing and weather or not injuries might be affecting player statistics. By tracking these metrics, our client can make informed decisions on whether to keep underperforming players on the roster if they are injured and seeing if certain player slumps are a result of injury. Additionally, if there are players that are injured while also not putting up numbers (runs), management could decide it would be worth it to give them time to recover as they are currently not vital to team success.

#7. List the total score, the amount of homeruns included in the total score, and the location for all games played in the 2023 season

Description: The purpose of this query is to count up the total Braves scores across all games in a season while also counting up the sum of home runs made and giving the locations of where the games were played. This query could be used as a tool indicating performance evaluation for the team across the season. Based on this, our client can see multiple trends such as player development, what locations the team excels at, etc.

#8. List out the location and game score of all games whos average score is greater than the average score of all games played in the 2023 season

Description: This query sees which games our clients team played exceptionally well in. From the results of this query, our client will be able to see times of success and use that information to improve upon strategic decisions. For example, if this query shows the Braves excel in games where they have one practice and one rehab pre-game, management could adjust their training schedule to try and replicate the results. It could also be used to see if we perform better at home vs. away, on far away road games or closer games, and if they excel when they follow certain strategies. 

#9. List out the names of coaches and their salary who make more than the average salary of all coaches. Order the salaries from highest to lowest. 

Description: The purpose of this query to see which coaches are making more than the average coaching salary within the organization. It provides insight into the teams salary distribution, and our client could use this to solidify their exceptional coaches, see if there are coaches that are overpaid, and overall make sure all their money is being used in a beneficial way rather than being wasted. If our client noticed a coach that is being overpaid and does the same thing as other coaches and they don't determine that they are absolutely essential, they could rework their contract to free up some money.

#10. List out first and last name of the player and type of equipment for players who have equipment with the condition broken. Additionally list out the practice duration for practices between 2 and 3 hours and the facility name and facility type that the practices took place in. Order by the practice duration. 

Description: This queries purpose is to see if players are being affected by broken equipment. Our client can take these results to implement proactive measures by providing more equipment to ensure the maximum productivity is reached in practice and no money is being wasted.

**Database Information:**
Name of the database: ns_Sp24_61608_Group2
Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Qx();




