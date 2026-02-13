# Asteroids (Pygame)

A small clone of the classic Asteroids game built with Python and Pygame.

This is my second guided project on [boot.dev](https://www.boot.dev).

About
-----
Build a clone of the classic Asteroids game using Pygame and object-oriented programming concepts. This guided project helps me understand how to use Pygame to create a game loop, handle user input, and manage game state. You'll also learn how to use object-oriented programming to create game objects and manage their interactions.


Features
--------
- Player movement (rotate, thrust, reverse)
- Shooting projectiles
- Asteroids that split when shot
- Simple collision detection and game-over

Requirements
------------
- Python 3.13 or newer
- Pygame 2.6.1


Controls
--------
- `A` — rotate left
- `D` — rotate right
- `W` — thrust forward
- `S` — thrust backward
- `Space` — shoot

Project Structure
-----------------
- `main.py` — entry point and game loop
- `player.py` — `Player` class and input handling
- `asteroid.py` — `Asteroid` class and splitting logic
- `asteroidfield.py` — manages asteroid spawning
- `shot.py` — projectile (`Shot`) implementation
- `circleshape.py` — basic circle-based shape utilities
- `constants.py` — game constants (screen size, speeds, radii)
- `logger.py` — simple event/state logging used by the game



