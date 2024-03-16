Title: Shooter Game Documentation

Description:
This documentation provides a detailed explanation of the code for a simple 2D shooter game developed using Pygame. The game features a player character that can move left, right, jump, shoot bullets, and throw grenades. The player must navigate through levels, defeat enemies, and collect items to progress.

Code Structure:
The code is organized into several sections, each responsible for different aspects of the game:

1. Initialization:
   - Import necessary libraries: pygame, mixer, os, random, csv, button.
   - Initialize Pygame and set up the game window.

2. Constants and Variables:
   - Define constants such as screen dimensions, frame rate, gravity, tile size, etc.
   - Initialize variables for game state, player actions, sound effects, etc.

3. Load Assets:
   - Load images for buttons, background, tiles, characters, bullets, grenades, item boxes, etc.
   - Load sound effects for jump, shoot, grenade, etc.

4. Helper Functions:
   - Define helper functions for drawing text, background, resetting levels, etc.

5. Class Definitions:
   a. Soldier: Represents the player and enemy characters.
   b. World: Represents the game world and processes level data.
   c. Decoration: Represents decorative elements in the game world.
   d. Water: Represents water tiles in the game world.
   e. Exit: Represents the exit tile that triggers level completion.
   f. ItemBox: Represents boxes containing items such as health, ammo, grenades.
   g. HealthBar: Represents the health bar displayed for the player.
   h. Bullet: Represents bullets fired by the player and enemies.
   i. Grenade: Represents grenades thrown by the player.
   j. Explosion: Represents explosion effects triggered by grenades.
   k. ScreenFade: Represents screen fading effects for intro and death screens.

6. Initialize Game Elements:
   - Create sprite groups for enemies, bullets, grenades, explosions, item boxes, etc.
   - Load level data from CSV files and create the game world.
   - Initialize the player character and health bar.

7. Main Game Loop:
   - Handle user input for movement, shooting, and grenade throwing.
   - Update game elements such as player, enemies, bullets, grenades, etc.
   - Check for collisions, level completion, and player death.
   - Draw background, world map, UI elements, and sprites on the screen.
   - Manage screen scrolling and fade effects.
   - Handle events such as quitting the game or restarting after death.

8. Game Initialization:
   - Display the start menu with options to start the game or exit.
   - Transition to the game screen when the game starts.

9. Event Handling:
   - Process keyboard events for player movement, shooting, jumping, etc.
   - Handle quitting the game and other keyboard events.

10. Display and Update:
   - Update the display with changes made during the game loop.
   - Update the Pygame display surface to show the current frame.

11. Game Over and Restart:
   - Display a death screen with options to restart or exit after the player dies.
   - Restart the game when the player chooses to restart.

12. Quitting the Game:
   - Quit Pygame and exit the game loop when the user chooses to exit.

Usage:
To run the game, execute the Python script containing the provided code. Ensure that Pygame is installed on your system.

Dependencies:
- Pygame: A set of Python modules designed for writing video games.
- Other standard Python libraries such as os, random, csv, etc.

Contributors:
This code was developed by an individual developer and may be modified or extended by other contributors.

License:
This code is provided under an open-source license, allowing for modification, redistribution, and use in personal or commercial projects, with proper attribution to the original author.

Disclaimer:
The code provided in this documentation is for educational purposes only and may contain bugs or incomplete features. Use at your own risk.

