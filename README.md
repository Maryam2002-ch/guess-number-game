# 🎯 Guess the Number Game

A fun and interactive command-line number guessing game written in Python. The computer picks a random number between 1 and 100, and you try to guess it!

## 🎮 How to Play

1. Run the program
2. The computer will think of a random number between 1 and 100
3. Enter your guess
4. Get hints: "Too High ⬆️" or "Too Low ⬇️"
5. Keep guessing until you find the correct number
6. Play as many rounds as you want!

## ✨ Features

- Random number generation each round
- Input validation (handles letters, empty inputs, out-of-range numbers)
- Helpful feedback with emojis (⬆️ ⬇️ 🎉)
- Play again option after each round
- Clean and modular code structure

## 🚀 How to Run

Make sure you have Python installed (version 3.6+), then run:

```bash
python guess_number.py

```
## 📝 Example Gameplay
I'm thinking of a number between 1 and 100. Try to guess it!

Your guess: 50
⬇️ Too low. Guess again.

Your guess: 75
⬆️ Too high. Guess again.

Your guess: 62
🎉 62 is correct! You got it!

Would you like to play again? (yes/no)

## 📁 Project Structure
guess-number-game/
├── guess_number.py    # Main game logic
└── README.md          # Project documentation

## 🛠️ Code Highlights
Uses random.randint() for number generation

try/except for error handling

Modular functions for better readability

Input validation for numbers between 1-100

## 📄 License
Feel free to use, modify, and share this project for learning purposes.

⭐ If you enjoyed this game or found it helpful, give it a star!
