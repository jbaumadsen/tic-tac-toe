# tic-tac-toe
## Roadmap of Future Improvements
I would refactor the game to

-prevent a player from playing a square that had already been played
-stop play once a player has won
-add a button to start a new game once a player has won
-not mount the "we have a winner" h1 until a player has won
-simplify the checkForWinner to only check the current player's moves for a win
-change the return of checkForWinner to 0 for player O wins, 1 for player X wins, or 2 for No Winner Yet


Once the return for checkForWinner was changed, I would pass a winner prop to Square and wrap the contents of the Square's onClick in an if statement that requires "(!filled && winner == 2)" this would prevent a square from being played multiple times and squares being played after a player won.
