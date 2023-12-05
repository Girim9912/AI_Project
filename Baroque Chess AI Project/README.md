# Baroque Chess AI wuth Alpha_Beta_Pruning

This is a collaborative project between me and my fellow student. 
 We developed a bot for playing Baroque Chess, which is basically Chess with much crazier pieces and rules (The typical rules can be seen on [Wikipedia](https://en.wikipedia.org/wiki/Baroque_chess)).  The main code for the bot is in `terminator_Baroque_Chess_Player.py`, which uses the minimax search algorithm with alpha-beta pruning for finding the most optimal move given a board state.  In this Project Zobrist hashing is also implemented, which is helped to reduce the search time by at least 30%.  



# Script to Run the code

`BaroqueGameMaster.py` is used to conduct a Baroque Chess game between two bot Players. In this Game we made use of Alpha_Beta Pruning algorithm to find effective moves. To run this, use the  following template:

An example would be:
```
python BaroqueGameMaster.py terminator_Baroque_Chess_Player terminator_Baroque_Chess_Player 5
```

Running this starts printing a game in the terminal between two bot players where each move needs to be made within 5 seconds.



