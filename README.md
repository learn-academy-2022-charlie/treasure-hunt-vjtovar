# React Treasure Hunt Game

### Remember:
- Pseudocode!!
- Ask clarifying questions

### User Stories
- As a user, I can see a page with a 3 by 3 grid board game with a question mark in each square.
    - Branch: board-game-vt
    - Rendering one square with the Square componet
    - Mapped over the Square to get nine squares
    - Styled the group of squares using flexbox
    - Passed the value of the array in state to Square (aka "?")
    - Cleaned up the warning by adding a key with the index of each  item in the array.
- As a user, when I click on one of the question marks an alert appears with the index position of that question mark in the array.
    - Branch: alert-index-vt
    - Pass index to the square component
    - Add an onClick to Square
    - Pass a method from App to Square to alert the index
- As a user, when I click on one of the question marks instead of the alert the question mark turns into a tree emoji.
    - Branch: tree-emoji-vt
    - DEstructure board out of state
    - Update the board value for the particular
    - USe emoji keoboard: control + command + space bar
    - Set state with updated value
- As a user, if I select the winning square the question mark will become a treasure emoji and if I select the losing square the question mark will become a bomb emoji.
    - Branch: win-lose-vt
    - Create a random number for treasure and set state
    - Add a conditional to the handleGamePlay to update the treasureLocation with a diamond emoji
- As a user, I can click on a “Play Again” button that will restart the game.
- As a user, I can see a counter that shows how many guesses I have left. The counter starts at 5 and decrements one every time I click on a square that is not the treasure nor the bomb.
- As a user, I can see a message informing me that I won the game if I select the square that contains the treasure.
- As a user, I can see a message informing me that I lost the game if I select the square that contains the bomb.
- As a user, I cannot continue to play the game after I win or lose.
- As a user, I can see a message informing me that I lost the game when I run out of turns (the counter reaches zero).
