# NFL_LT_or_DE

In this project, I try to determine which is the second most important position in the National Football League (NFL).  Obviously, quarterback is the #1 most crucial position in football, if not all of sports.  But there is debate of which is the second most critical.  Usually the debate centers around two positions: Left Tackle and Defensive End/Outside Linebacker.  In other words, is protecting your own quaterback or going after your opponent's quartback a bigger catalyst in whether a team wins or loses?

To answer this, I collected data from the 2019 season, looking at stats pertaining to sacks allowed by each team, sacks forced by each team, and wins per team.  After conducting statistical analyses (using Excel, SQL, and R) on these datasets, I can conclude that -- all other things being equal -- Left Tackle is a more important position than Defensive End when it comes to winning games.  

When you visualize the data (using Tableau), you can see that the slope of the scatterplot of teams in the "Sacks Allowed" graph is steeper than the scatterplot in the "Sacks Forced" graph.  In addition, the R-squared of the trend line on the "Sacks Allowed" graph is 0.27 while on the "Sacks Forced" graph it's 0.12, indicating that the variable used in the former graph is a better fit for the model than the variable used in the latter one.  In other words, sacks allowed is a better measure of team success (or failure) than sacks forced.

Note: This is meant to be a simple project, not an in-depth evaluation, hence the use of only one year of data.  In order to ensure a more precise result, I would use more years of data, probably at least 5, in my analysis.
