# Best Untouched Fantasy League Team via ILP

This works shows the best selection of Fantasy Premier League players over the course of the whole season. It looks into finding the team that will score best throughout the season if no transfers are to be applied. 

Fantasy Premier League is a popular game, where each user selects a set of real-life soccer players, and based on their real-life performances, he receives a certain score for each of them. A player in this game is called a manager. 

The game follows the actual English Premier League that is played over the course of 38 gameweeks. At the beginning of the league (gameweek 1), the manager is to choose any player to start with (as long as they are within budget and satisfy some other constraints stated later). He/she is allowed to make as much changes to his squad before the beginning of the first gameweek. Before each gameweek, each manager is allowed one unpenalized transfer move, in which he can remove one player from his team and replace him by another one. 

Transfers play a crucial role in the game. However, an interesting question would be: Can a manager leave his squad untouched from the beginning of the season and still score well? This question actually gives rise to another one. What is the best Fantasy League Team that is kept untouched (no changes done it) throughout the course of the season? Some like to call such a team a Zombie Team :) 

Consequently, the aim of this work is to determine which Fantasy Premier League squad that undergoes no changes throughout the season is the best. The best team is in other words the highest-scoring team. Scores of teams are determined by summing the individual scores of each player in the team. 

A Fantasy Premier League squad consists of 15 real-life Premier League players. However, during a give gameweek, scores are determined only by 11 players that the manager chooses to "start" in the gameweek. A manager has the freedom to choose the 15 players in his team but must take into account:

1) Budget constraint: each player has a certain starting price (in millions of pounds). The cost of the entire Fantasy team must not exceed 100m. 
2) Team constraint: no more than 3 players from any real-life team must be chosen at a given time. For example, in a Fantasy Premier League squad, no more than 3 players from the actual Premier League team Manchester United can be chosen at a given time. Of course, the manager is welcome to choose less any amount less than 3. He can choose not to take any player from Manchester United. 
3) Position Constraints: Players in the Fantasy Premier League are assigned 1 out of 4 positions (Goalkeeper, Defender, Midfielder, Forward). The position distribution of the 15 players must be: 2 goalkeepers, 5 defenders, 5 midfielders and 3 forwards. In each starting 11, 1 must be a goalkeeper, 3-5 must be defenders, 2-5 must be midfielders and at least 1 must be a forward. 
