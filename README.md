# Snake Game

## What it does
A classic Snake game made with Python's turtle module where you eat food, grow longer and try to beat your saved high score.

## Features
- Control the snake with the arrow keys
- Snake grows every time it eats food
- Score and high score shown on screen, high score saved in a file
- Game over when the snake hits the wall or itself

## Tech used
Python 3 | turtle | time | random

## How to run
```bash
git clone https://github.com/Arya-Rajvansh/Snake-Game.git
cd Snake-Game
pip install -r requirements.txt
python main.py
```
Press the arrow keys to move. Click the window after game over to close it.

## Screenshot
[add screenshot]

## What I learned
- Object-oriented programming with classes (Snake, Food, Scoreboard) and inheritance from Turtle
- Building a game loop with screen.update() and time.sleep()
- Detecting collisions using distance() and screen boundaries
- Saving and loading a high score with file handling
- Splitting code into modules inside a src folder

## Status
✅ Complete
