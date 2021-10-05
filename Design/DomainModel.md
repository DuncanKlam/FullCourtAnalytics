# Design

![Domain model](https://github.com/DuncanKlam/FullCourtAnalytics/blob/main/Design/FullCourtDomainModel.png)

- User
    > This class will have account information; email, password.
- Admin
    > This class will have information for an admin and different authorization than the normal user.
- Player
    > This class will have a player's information, statistics, and attributes. 
- Coach
    > This class will have a coach's information.  
- StatCalculator
    > This class will calculate the statistics of any player given to it. 
- ShotChart
    > This class will be a visual representation of efficiency for a player, from specific areas on the court. 
- Game
    > This class will hold game stats, both teams, box score, game report, etc.
- GameAnnotator
    > This class will be what administrators use to annotate and break down a basketball game clip by clip. 
