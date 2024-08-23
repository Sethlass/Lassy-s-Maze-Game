# Lassy's Maze Game

Welcome to Lassy's Maze Game, a retro-style maze game inspired by one of the earliest video games. This is my second game in a series of 10, where I aim to recreate 10 of the oldest video games. Notably, this is also my first time coding with HTML, and I'm excited to share this project with you!

## How to Install and Play (For Windows Users)

### Installation & Play
1. **Download the Game File**: Simply download the `MazeGame.html` file from this repository.
2. **Open the Game**:
   - Double-click on the `MazeGame.html` file.
   - It should automatically open in your default web browser (preferably Chrome) where you can start playing immediately.

### How to Play

#### Objective
Your goal is to navigate the maze, collect all the gold blocks, and then reach the finish line. The game starts with the finish line locked, and it will only unlock once all three gold blocks have been collected.

#### Controls
- **W:** Move Up
- **A:** Move Left
- **S:** Move Down
- **D:** Move Right
- **Shift:** Hold Shift to increase speed

#### Rules
- **Collect Gold Blocks:** There are three gold blocks scattered around the maze. You must collect all of them before you can head to the finish line.
- **Finish Line:** The finish line starts locked and will unlock once you collect all the gold blocks.
- **Avoid Walls:** If you crash into a wall, the game will restart, and your current lap time will not be recorded.
- **Complete the Lap:** After collecting all gold blocks, reach the finish line to complete the lap and record your time.

### Game Features
- **Lap Timer:** The game records the time it takes for you to complete a lap. Only successful lap completions are recorded.
- **Top Scores:** The game maintains a leaderboard displaying the top 5 lap times.

## How the Game Works

### Game Loop
The game operates in a continuous loop that listens for player input, updates the position of the car, checks for collisions, and renders the game state on the screen. The loop will continue until the player completes the lap or crashes into a wall.

### Gold Blocks and Finish Line
Gold blocks are placed at specific positions within the maze. When the car's position coincides with a gold block, that block is marked as collected and removed from the screen. The finish line remains locked until all gold blocks are collected.

### Collision Detection
The game checks for collisions between the car and the maze walls or the finish line. If a collision with a wall occurs, the game resets. If the car reaches the finish line after collecting all gold blocks, the lap is completed, and the player's time is recorded.

### Leaderboard
The game tracks the best 5 lap times, displaying them on a leaderboard. Players can see their best performances and strive to improve their times.

## About the Project

This game is part of a larger project where I recreate 10 of the oldest video games. **Lassy's Maze Game** is the second in the series, focusing on the simplicity and challenge of early maze-based games. This is also my first time coding with HTML, making this project a valuable learning experience. My goal is to understand the mechanics and design principles of classic games while recreating them with modern tools.

Stay tuned for more games as I continue this journey through the history of video games!

---

Feel free to contribute, report issues, or provide feedback. Happy gaming!
