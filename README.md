# 🎯 Number Guessing Game (Tkinter)

A simple Number Guessing Game built using Python and Tkinter. The program randomly selects a number between 1 and 10, and the player tries to guess it. The game provides hints to help the player find the correct number.

## Features

- Simple graphical user interface (GUI) using Tkinter
- Random number generation
- Hint system:
  - "Try a higher number"
  - "Try a lower number"
- Success message when the correct number is guessed
- Exit button to close the application
- Attractive pink-themed interface

## Technologies Used

- Python 3
- Tkinter (GUI Library)
- Random Module

## Project Structure
Number-Guessing-Game/
│
├── number_guessing_game.py
└── README.md

## How It Works

1. The application generates a random number between **1 and 10**.
2. The user enters a guess in the input field.
3. After clicking the **Guess** button:
   - If the guess is correct, a congratulatory message appears.
   - If the guess is too low, the game suggests a higher number.
   - If the guess is too high, the game suggests a lower number.
4. The **Exit** button closes the application.

## Installation

### Prerequisites

Make sure Python 3 is installed on your system.

Check Python version:

```bash
python --version
Run the Project
1.Clone the repository:
git clone https://github.com/your-username/Number-Guessing-Game.git
2.Navigate to the project folder:
cd Number-Guessing-Game
3.Run the application:
python number_guessing_game.py
Example
Guess a number between 1 and 10
Input: 5
Output: Try a higher number.

Input: 8
Output: Congratulations! You guessed it!
