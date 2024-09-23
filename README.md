# Project Proposal

## Inspiration

Sports are a vast source of complex data and statistics and something I find myself watching quite often, which led to the passion behind this project. Due to the high scoring and unpredictability of the NBA, I have devised an idea to analyze this further to gain a better and deeper understanding of not only the sport but the statistics that make it. 

## Data Collection and Models

Data collection for the project will be from various sports websites but mainly that of NBA.com (the official league website) for the official stats of the players and teams. Just off some basic background research I have found a resource known as API-NBA which should provide me all the necessary statistics of players/teams. https://rapidapi.com/api-sports/api/api-nba https://github.com/public-apis/public-apis?tab=readme-ov-file I will be using a classifier approach for the machine learning model. My aim is to use a random forest classification model there are a multitude of reasons however one that caught my eye was that it features feature ranking as well as it utilizes a bunch of decisions trees to try and cover every case. There will be feature vectors containing that of each of the main stat categories based on team game averages. There can be mulitple matrices, one containing historical information between the teams, matrices with the row representing a game and columns being the respective stat categories based on team averages per game. As for the tensors I believe a 3D tensor regarding teams, their performance and the season length would help to gather team statistics. Additionally we can add a fourth dimension, the players, in order to gain a better understanding from the player standpoint.

## Computer Vision (CV)

Furthermore, for the computer vision aspect of this project I will be doing an overlay during games. This can be achieved using bounding boxes and jersey numbers to link the player to the team sheet. I can also look at the colours of the jerseys to determine the team and maybe look at the overall dominance (floor spacing, etc.). I will detect players on the floor using cv and then using that data, fetch their historical statistics and then run the model to see the probability of which team wins.

## Natural Language Processing (NLP)

Moreover, the natural language processing aspect will entail that of a live chat bot. The aim with this chatbot is to allow users to type the names of players to view their historical stats against the enemy team. Their recent performance as well as historically and their live performance it can make an educated decision as to what will occur. I am also looking to use this chat bot to allow users to manually switch to view a player of their choosing to and to display all their stats. 

## Reinforcement Learning

Honestly, as of right now I am not quite sure how this part of the project can be implemented in this scope however, I am more than open to suggestions and will try to incorporate this into said project as more information is apparent. Any feedback for this portion would be greatly appreciated.