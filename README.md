# Weekend Game

## Introduction

Weekend is an arcade-style game developed in Python using the Pygame library. In this game, players navigate through a dynamic environment, controlling a party-goer character to dodge incoming threats represented by beer icons while trying to score points by shooting them down.

## Installation

To run the game, you'll need Python and Pygame installed on your system. If you don't have them installed, you can get Python from [python.org](https://www.python.org/) and install Pygame by running `pip install pygame` in your command line.

## Usage

Clone the repository to your local machine and navigate to the downloaded folder. Run the game script with Python:
```shell
python weekend_game.py
```


## Features

- Dynamic Background Music: Enhances gameplay with continuous background music to keep the energy high.
- Visuals and Sound Effects: Immersive visuals and responsive sound effects for actions like shooting and collisions.
- Player Mechanics: Smooth player controls for moving left and right, and for shooting.
- Enemy Mechanics: Multiple enemy types with varying speeds and movement patterns.
- Scoring System: Keep track of your score as you hit enemy icons.
- End Game Conditions: The game ends with a fun twist, marking the dreaded arrival of Monday.

## Technical Components

- Pygame Initialization: Sets up the game environment, including the display window, game icons, and title.
- Asset Management: Handles loading and rendering of game graphics and audio files.
- Game Variables: Defines and initializes the player, enemies, bullets, and scoring system.
- Collision Detection: Implements collision detection using mathematical functions to end the game or increment the score.
- Game Loop: The heart of the game, it processes input events, updates game state, renders the game objects, and refreshes the screen.

## Code Structure

- pygame.init() to start the game engine.
- A game window created with pygame.display.set_mode().
- Assets (images and sounds) are loaded using pygame.image.load() and pygame.mixer.Sound().
- A main game loop which handles events, updates the game state, and renders the graphics.
- Input handling for player movement and shooting.
- Collision detection to register hits between bullets and enemies.

## Customization

Players are encouraged to customize the game by adding new assets, levels, and features. Modify the game variables to create new challenges or tweak the existing gameplay.

# Contact Information


🌐 Website: https://javierblancotech.com/

📧 Email: info@javierblancotech.com

👉🏼 LinkedIn: https://www.linkedin.com/in/javierblancotech/

Enjoy the game ! 😜
