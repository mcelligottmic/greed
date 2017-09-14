# greed
java based game 

Greed
The game of take all - win all

Players: 2-4
Style: turn based; strategy; puzzle

Players start off in a queue and will be uniquely numbered.
There is a queue of items that will move towards the players.
The first 7 items in the queue are visible to all players, but the rest are hidden.
Each player will take a turn taking the closets set of items starting with player 1. 
The players MUST take a set of 1, 2, or 3 of the next items in queue.
Upon selecting the value of the set a player will remove those items from the queue. (would a bomb stop items after it from being selected by the player?)
All items in a set will be activated by the player and removed from the queue.
Item Queue:
There are 100 items in a game.
10 items will be bombs
20 will be coins
70 will be fruit
Bombs: explode when a player grabs it. This take out a player’s life points.
Fruits: does nothing
Coins: an item that increases your score by 1 and allows you to buy power-ups!
If a player life drops to zero they are removed from the queue.
End condition:
The game ends when one player (team) is remaining. All other players (teams) health is at 0.
The player (team) with the most points (total number of coins collected not current amount) is the winner.
