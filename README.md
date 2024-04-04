## FlowerPower
## Overview
This Java program, called FlowerPower, is a simple game implemented using Java Swing. In this game, the player interacts with a garden by solving math problems to grow flowers and avoiding weeds. The game provides a user-friendly interface where the player's name and score are displayed, and the player can choose to play again or exit the game.

## Key Features
Interactive Garden: The game provides a virtual garden environment where the player can grow flowers and avoid weeds.

Math Problem Solving: To grow flowers, the player needs to solve math problems correctly. Incorrect answers may lead to the growth of weeds.

Scoring System: The player's score increases when they grow flowers and decreases when weeds are grown.

Game Over Mechanism: The game ends when the garden is full or when the player chooses to exit. Upon game over, the player can choose to play again.

## How to Play
Enter Your Name: When the game starts, the player is prompted to enter their name.

Solve Math Problems: Math problems are displayed, and the player must input the correct answer using the keyboard.

Grow Flowers, Avoid Weeds: Correct answers lead to the growth of flowers, while incorrect answers lead to the growth of weeds. The player's score is updated accordingly.

Game Over: The game ends when the garden is full. The player can choose to play again or exit.

## How It Works
The FlowerPower class extends JPanel and implements the KeyListener interface to handle user input.

The garden is represented by the Garden class, and the math problems are managed by the MathProblem class.

The game state is tracked to control the flow of the game, such as displaying math problems, updating the garden, and handling game over scenarios.

User input is processed to determine whether to grow flowers or weeds, update the score, and handle game over conditions.
