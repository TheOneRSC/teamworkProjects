It's time for the teamwork projects and we are responsible for gathering the teams. First we will receive an integer - the count of the teams we will have to register. We will be given a user and a team, separated with “-”.  The user is the creator of the team. For every newly created team we should print a message: 

"Team {teamName} has been created by {user}!".


Next, we will receive an user with a team, separated with "->", which means that the user wants to join that team. Upon receiving the command: “end of assignment”, you should print every team, ordered by the count of its members (descending) and then by name (ascending). For each team, we have to print its members sorted by name (ascending). However, there are several rules:

•	If an user tries to create a team more than once, a message should be displayed: 

-	"Team {teamName} was already created!"

•	A creator of a team cannot create another team – the following message should be thrown: 
-	"{user} cannot create another team!"

•	If an user tries to join a non-existent team, a message should be displayed: 
-	"Team {teamName} does not exist!"

•	A member of a team cannot join another team – the following message should be thrown:
-	"Member {user} cannot join team {team Name}!"
In the end, teams with zero members (with only a creator) should disband and we have to print them ordered by name in ascending order.


•	 Every valid team should be printed ordered by name (ascending) in the following format:

"{teamName}:

-{creator}

-- {member}"
