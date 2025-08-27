# Asteroids Game

A classic Asteroids arcade game built with Python and Pygame.

## Description

This is a recreation of the classic Asteroids arcade game where you pilot a spaceship through an asteroid field, shooting asteroids to survive. Large asteroids split into smaller, faster ones when destroyed, creating an escalating challenge.

## Features

- Player-controlled spaceship with rotation and thrust
- Shooting mechanics with bullet physics
- Asteroid splitting system (large → medium → small)
- Collision detection between bullets, player, and asteroids
- Wrapping screen boundaries
- Asteroid field generation

## Controls

- **A/D**: Rotate ship
- **W/S**: Thrust forward or backward
- **Space**: Shoot

## Mechanics

- Large asteroids split into 2 medium asteroids when shot
- Medium asteroids split into 2 small asteroids when shot
- Small asteroids are destroyed completely when shot
- Split asteroids move faster and in random directions
- Player is destroyed on collision with any asteroid

## Project Structure

- main.py - Main game loop and initialization
- player.py - Player ship class
- asteroid.py - Asteroid class with splitting logic
- shot.py - Bullet/projectile class
- circleshape.py - Base class for circular game objects
- asteroidfield.py - Manages asteroid spawning
- constants.py - Game constants and configuration

## Credits

Built as part of the Boot.dev Python course