# Turtle Graphics Playground 🐢🎨

This repository showcases two beginner-friendly Python projects built using the `turtle` graphics module. These projects helped me explore visual programming, randomness, and basic user interaction in Python.

---

## 📌 Projects Overview

### 🎯 1. Dot Art Generator

Inspired by Damien Hirst's famous dot paintings, this script creates a 10x10 grid of colorful dots. Each dot is randomly colored from a predefined list.

**What I Learned:**
- Drawing with the `turtle` module
- Using RGB color mode with `screen.colormode(255)`
- Looping for 2D drawing (nested loops for rows/columns)
- Generating randomness with the `random` module
- Basic 2D positioning logic using `.goto()` and `.xcor()/ .ycor()`
- Introduction to using color extraction with `colorgram.py` (optional)

### 🐢 2. Turtle Race Game

A simple race simulation where six turtles race across the screen, and the user bets on which one will win.

**What I Learned:**
- Handling user input using `screen.textinput()`
- Creating multiple `Turtle` objects with unique properties (color, position)
- Working with lists to manage multiple game elements
- Conditional logic to determine the winner
- Controlling game flow with flags (`is_race_on`)
- Randomized movement for game dynamics

---

## 🧠 Key Concepts Practiced

- Turtle graphics and canvas manipulation
- Loops and conditionals in game logic
- Object-oriented basics (instantiating and using Turtle objects)
- Randomization for creative and game purposes
- Event-driven programming and user input
- Use of `screen.exitonclick()` to keep the program open until clicked

---

## 🛠️ Technologies Used

- **Python 3**
- **turtle** (built-in, for graphics)
- **random** (standard library, for randomness)
- **colorgram.py** *(optional, for color extraction)*
- **Pillow (PIL)** *(installed but not used in current code)*

---

## 🚀 Getting Started

1. Clone the repository or copy the scripts.
2. Make sure Python 3 is installed.
3. (Optional) Install `colorgram.py` and `Pillow` if you want to extend the Dot Art project:
   ```bash
   pip install colorgram.py Pillow
