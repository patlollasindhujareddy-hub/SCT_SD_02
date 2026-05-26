# SCT_SD_02
An interactive Number Guessing Game implemented in C. Generates a dynamic random number and tracks user attempts. Built for Task 02 of the SkillCraft Technology internship.
# Number Guessing Game (C Implementation)

## 📌 Project Overview
This project is an interactive, console-based **Number Guessing Game** written in **C**. 

Developed as **Task 02** during my internship at **SkillCraft Technology**, this project showcases standard game loop mechanics, dynamic random number generation, and user-input processing.

## 🚀 Features
- **Dynamic Randomization:** Generates a unique target number between 1 and 20 every time the program runs.
- **Attempt Tracking:** Keeps a live count of how many guesses the user takes to find the correct answer.
- **Infinite Game Loop:** Continues to prompt the user until the exact number is guessed, featuring an efficient loop break strategy.

## 🛠️ Core Concepts Demonstrated
- **Randomization:** Utilizing `<stdlib.h>` and `<time.h>` to seed and generate pseudo-random numbers via `srand()` and `rand()`.
- **Control Flow:** Implementation of an infinite `while (1)` loop coupled with conditional evaluations (`if-else`).
- **Data Mutation:** Direct state handling for counting user execution cycles (attempts).

## 💻 How to Compile and Run
You can quickly compile and test this project via your terminal using any standard C compiler (like `gcc`):

```bash
# Compile the program
gcc guessing_game.c -o game

# Run the executable
./game
