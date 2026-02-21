# Motivation for this project
Currently, I am programming more in Python in my spare time and would like to delve deeper into the programming language.

As part of the Boot.dev learning platform, there is a small project where a “Classic Asteroids” clone was built, which helped me achieve my goal. It was mainly about OOP. For the physics and mathematics of the game, I was able to access code from the platform, so OOP is more in the foreground.

# What is Asteroids?
Asteroids is a simple video game, based on the classic Asteroids. If you've never played before, you can take a look at this (slightly different from our) version of the game.
https://www.echalk.co.uk/amusements/Games/asteroidsClassic/ateroids.html

# What have I learned?
- build a little python game with Pygame
- setup python projects with uv
  - manage technical dependency
- object-oriented programming concepts
  - player
  - asteroids
  - fields
- gameloop
- logging game state
- math 
  - moving asteroids and player
  - collisions
  - shooting
  - rate/limit
  - descrution
  - splitting

# How to run the game
1. Run the game: `uv run main.py`

# Project Structure
- `main.py`: The entry point of the game. It contains the main game loop.
- `player.py`: Defines the Player class, which represents the player's ship.
- `asteroid.py`: Defines the Asteroid class, which represents the asteroids.
- `asteroidfield.py`: Manages the asteroids in the game.
- `shot.py`: Defines the Shot class, which represents the player's shots.
- `circleshape.py`: A helper class for circle-based collision detection.
- `constants.py`: Contains the constants used in the game.
- `logger.py`: A simple logger for logging game events.
