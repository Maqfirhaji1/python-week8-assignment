# PLP Python Week 8 — Personal Mini-Toolkit

## Project Overview

This project is my Week 8 final Python project for the PLP Python Programming course. It combines variables, input/output, conditionals, loops, lists, functions, and user interaction into one menu-driven Personal Mini-Toolkit.

The toolkit contains three tools:

- **Calculator** — Performs addition, subtraction, multiplication, and division.
- **To-Do List** — Allows users to add, view, and remove tasks while the program is running.
- **Number Guessing Game** — Generates a random number and lets the user repeatedly guess until they find it.

## Files

- `toolkit_plan.txt` — Contains the project plan, menu design, tools, and Python concepts used.
- `toolkit.py` — Contains the complete menu-driven Personal Mini-Toolkit.
- `README.md` — Documents the project, how to run it, and my development reflection.
- `screenshots/` — Contains screenshots showing the menu and each tool working.

## How to Run

Make sure Python 3 is installed.

Open a terminal in the project folder and run:

```bash
python toolkit.py


If your system uses python3, run:

python3 toolkit.py


The program will display a menu:

Please choose a tool:

1. Calculator
2. To-Do List
3. Number Guessing Game
4. Quit


Enter the number of the tool you want to use.

Features
Calculator

The calculator accepts two numbers and lets the user choose addition, subtraction, multiplication, or division. It also checks for division by zero and invalid number input.

To-Do List

The to-do list uses a Python list that changes while the program runs. Users can add tasks, display all tasks, and remove existing tasks.

Number Guessing Game

The guessing game uses Python's random module to generate a number from 1 to 20. A loop continues until the user guesses correctly, while conditionals provide "too high" and "too low" feedback.

Python Concepts Demonstrated

This project demonstrates:

Variables

Input and output

if, elif, and else

while loops

for loops

Lists

append()

remove()

Membership checking with in

Functions

try / except

Random numbers

f-strings

Menu-driven program design

The if __name__ == "__main__": pattern

Reflection

The hardest part of this project was organizing the different tools so that each one could finish and return control to the main menu correctly. The menu loop required careful use of if, elif, and else so that valid choices launched the correct tool while invalid choices produced a friendly message. One bug that took the most attention was making sure invalid number input did not crash the calculator or guessing game. I solved this by using try and except ValueError around the conversions that could fail. Building the to-do list also helped me understand how a list can change while a program is running. I would improve the project further by saving the to-do list to a file so that tasks would remain available after the program closes. With another week, I would also add more tools such as a unit converter and a password generator.

Repository Structure
plp-python-week8/
│
├── toolkit_plan.txt
├── toolkit.py
├── README.md
│
└── screenshots/
    ├── menu_invalid_choice.png
    ├── calculator.png
    ├── todo_list.png
    └── guessing_game.png

Author

PLP Python Programming — Week 8 Final Project

:::

## 4. Screenshots to submit

Create the folder:

```bash
mkdir screenshots


You should capture at least these four screenshots:

menu_invalid_choice.png — show an invalid menu choice and the program continuing normally.

calculator.png — show the calculator performing a calculation.

todo_list.png — show adding tasks, displaying them, and removing a task.

guessing_game.png — show the guessing game giving feedback and eventually accepting the correct answer.

Also make sure you capture the Quit path at least once during testing.

5. Final repository structure

Your GitHub repository should be exactly:

plp-python-week8/
│
├── toolkit_plan.txt
├── toolkit.py
├── README.md
│
└── screenshots/
    ├── menu_invalid_choice.png
    ├── calculator.png
    ├── todo_list.png
    └── guessing_game.png


Repository name:

plp-python-week8


LMS submission:

https://github.com/YOUR-USERNAME/plp-python-week8


Replace YOUR-USERNAME with your actual GitHub username.

Before submitting, open the repository URL in an incognito/private browser window and confirm that the files are visible without logging in.