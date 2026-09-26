# Aethel

A logic puzzle game that runs in the browser. Place sparks of light on the grid until every empty tile is lit.

Built with plain HTML, CSS and JavaScript, in a single file with no dependencies.

## Goal

Light up **every empty tile** on the board without breaking any of the rules below.

## Controls

- **Left click** on an empty tile to place a spark. Click it again to remove it.

## Rules

1. **Light:** a spark lights its entire row and column in all four directions until the beam hits a wall.
2. **No crossing beams:** two sparks must never light each other.
3. **Numbered walls:** a wall showing a number (0 to 4) must have **exactly** that many sparks on the tiles directly next to it (up, down, left, right).
4. **Spark limit:** some levels set a maximum number of sparks, shown in the counter next to the board.

## Worlds

- **World 1: Awakening** teaches the basic rules and numbered walls.
- **World 2: Mirrors** adds mirrors (╱ and ╲) that bend the light beam by 90 degrees.

## How to play

Download `Aethel_Puzzle.html` and open it in any modern web browser. Nothing to install.
