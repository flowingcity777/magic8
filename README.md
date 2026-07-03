# Magic 8-Ball

A simple, interactive Python program that simulates a classic Magic 8-Ball toy. This project explores fundamental programming concepts like control flow, conditional statements, and random number generation as part of the Codecademy Data Engineer career path.

## Project Overview
The Magic 8-Ball is a toy used for fortune-telling or seeking advice. This program prompts the user for their name and a yes-or-no question, then randomly selects one of nine possible answers (ranging from "Yes - definitely" to "Very doubtful") to reply with.

## Features
- **Dynamic Greeting:** Adjusts the output based on whether the user provides a name or chooses to ask a question anonymously.
- **Input Validation:** Error-handling to ensure the program doesn't run if a blank question is submitted.
- **Randomized Responses:** Utilizes Python's built-in `random` module to generate a unique fortune every time the script runs.

## Code Concepts Used
- **Variables:** Storing names, questions, and answers.
- **Conditionals (`if`/`elif`/`else`):** Handling various response outcomes and empty input scenarios.
- **Random Module (`random.randint`):** Generating random integers to map to specific answers.

## File Structure
- `magic8.py`: The main Python script containing the game logic.
- `.gitignore`: Standard rules to prevent tracking unnecessary environment files.
- `LICENSE`: MIT License.

## Prerequisites
To run this project, you only need Python installed on your machine. No external libraries or packages are required.

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/magic8-ball.git](https://github.com/YOUR_GITHUB_USERNAME/magic8-ball.git)
