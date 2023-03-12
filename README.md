# ticTacToe
A simple tic tac toe game built in React. Simply click on any square to place the "X" and start the game. First player to get 3 in a row, column, or on the diaganol
wins, and winner is displayed on the gameboard. 




##Roadmap to Future Improvements##

List of Improvements:
1. Fix the game so that each square can only be clicked once, then is locked in and cannot be changed later.
  --This could be done by adding a "marked" component to each square. Implement useState to update whether the square has been marked, and then remove the ability
    to click on it.
2. Add a Start Game/ New Game button, rather than refreshing the page everytime.
  --This could be implemented with a mount/unmount feature, again using useState to update whether or not the squares should be mounted
    

3. Lock the gameboard after a winner is determined. Right now, all that happens is an H1 says that a winner was determined. This can be vastly improved.
  -Generate Div that "pops up" and displays the winner, so it is more noticeable.
    --Put a full screen div in that sits on top of all other components and notifies who the winner is. This can be done mostly with CSS.
  
4. The game always starts with the same player, it would be nice to implement a "coin flip" feature that determines if player X or player O start the game.
    --Add a side component that generates either a 0 or 1 at the press of a button. Depending on which player is determined, that needs to be passed to the gameboard
      so that it correctly displays who move it is, and places the correct mark on the squares.
