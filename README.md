# Simon Game

The Simon game is a memory skill game that challenges players to remember and replicate sequences of colors. This project is a simple implementation of the Simon game using HTML, CSS, and JavaScript with jQuery.

## How to Play

1. **Starting the Game**:
   - Press any key to start the game.
   - The game will begin by displaying a sequence of one color.

2. **Gameplay**:
   - Watch the sequence of colors displayed by the game.
   - The sequence starts with one color and increases by one color each round.
   - Click on the colored buttons to replicate the sequence shown by the game.
   - If you successfully repeat the sequence, the game will add one more color to the sequence.
   - The game continues with the sequence getting longer and more challenging with each round.

3. **Losing the Game**:
   - If you click the wrong color, the game will end.
   - The screen will flash red to indicate a mistake.
   - The game will display "Game Over, Press Any Key to Restart".
   - Press any key to restart the game from level 0.

## Game Elements

- **Colors**: The game uses four colors - red, blue, green, and yellow.
- **Sequence**: Each level, a new color is added to the sequence.
- **User Interaction**: Players interact by clicking the colored buttons.

## Implementation Details

- **HTML**: The structure of the game interface.
- **CSS**: The styling of the game elements.
- **JavaScript/jQuery**: The game logic, including sequence generation, user input handling, and game state management.
