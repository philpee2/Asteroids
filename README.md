Asteroids
=========

**NOTE**: A new and improved version of this project can be found [here](https://github.com/philpee2/Functional-Asteroids)

## Overview

A simple variant on the original arcade game. A deployed version of Asteroids can be found [here](https://philnachumasteroids.firebaseapp.com/). 

Asteroids is built using HTML canvas, which draws objects at every frame. The game logic is written in Javascript, using Babel to transpile ES2015. 

## How to play

On the opening menu, click on a mode to select it, which begins the game. Use the left and right arrow keys to rotate the ship, the up arrow key to move, the space bar to fire, and the P key to pause/unpause.

## Notable Features

* There are multiple game modes to choose from
* The game has various sound effects
* Powerups are periodically placed in the game, which can be picked up for bonuses
* The game keeps track of the player's score, remaining lives, elapsed time, and score multiplier. These are displayed to the user depending on whether they're relevant to the current game mode.
* Upon spawning, the ship will be briefly invincible, indicated by flashing.

## Running locally

* Clone the repo
* `npm install`
* `webpack`
* `open index.html`

## Future Todos

### Asteroid physics

I've previously tried to get the asteroids to bounce off of each other with realistic collision physics based on the asteroids velocity and size (as a proxy for mass). The result was incredibly buggy, mostly due to the possibility of asteroids overlapping. This needs a lot more work.

### Additional powerups

I'd like to come up with more types of powerups. Temporary invincibility is one idea

### Alternative enemy types

Currently the only enemy type is simple asteroids. More complex and varied enemies would be interesting. 

### Weapon types

In addition to choosing a mode at the beginning of the game, players should also be able to choose a weapon type.
