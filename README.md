# Asteroids

A classic Asteroids arcade game implemented in Python using [Pygame](https://www.pygame.org/). Built as part of the [Boot.dev](https://www.boot.dev) Python curriculum.

## Features

- **Player Controls**:
  - `W` / `S` - Move forward and backward
  - `A` / `D` - Rotate ship left and right
  - `Space` - Shoot bullets (rate-limited cooldown)
- **Asteroids**:
  - Dynamically spawned around the screen edges with random trajectories.
  - Large asteroids split into two medium asteroids when shot.
  - Medium asteroids split into two small asteroids.
  - Small asteroids disappear when destroyed.
- **Collision Detection**: Circle-based collision detection for ship vs. asteroids and bullets vs. asteroids.

## Requirements

- Python 3.13+
- [uv](https://docs.astral.sh/uv/) (or pip)

## Running the Game

Run with `uv`:

```bash
uv run main.py
```
# Asteroids
