# Target-Game
This project is a simple target shooting game implemented using Pygame. The objective of the game is to click on the targets that appear on the screen before they disappear. The game tracks the number of targets you hit, your accuracy, and your speed.

### Installation
To run this game, you need to have Python and Pygame installed on your system.

### Usage
Simply run the target_game.py script to start the game. You can quit the game at any time by closing the game window or pressing any key.

### Gameplay
- Targets will appear randomly on the screen.
- Click on the targets to hit them before they shrink and disappear.
- The game ends when you miss a certain number of targets (lives).

### Game Mechanics
- Targets: Targets grow and shrink. You need to click them before they disappear.
- Scoring: The game tracks the number of targets you hit, your accuracy, and your hit speed (targets per second).
- Lives: You have a limited number of lives. Missing a target will reduce your lives. The game ends when you lose all your lives.
### Functions and Classes
-Target Class
  ### Attributes:
    -x, y: Coordinates of the target.
    -size: Current size of the target.
    -grow: Boolean indicating if the target is growing.
  #### Methods:
    - update(): Updates the size of the target.
    - draw(win): Draws the target on the given window.
    - collide(x, y): Checks if the given coordinates collide with the target.
  #### Functions
    - draw(win, targets): Draws the background and all targets.
    - format_time(secs): Formats the elapsed time for display.
    - draw_top_bar(win, elapsed_time, targets_pressed, misses): Draws the top bar with the game stats.
    - end_screen(win, elapsed_time, targets_pressed, clicks): Displays the end screen with final stats.
    - et_middle(surface): Returns the x-coordinate to center the given surface.
    - main(): Main game loop.

#### Screenshot
![gameplay.png]
![end-screwwn.png]
### License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy playing the Target Game! Feel free to contribute to the project by submitting issues or pull requests.







