# maturin-game
Maturin implementation of the guessing game

# Requirements
Python 3.7 or higher is required.
Rust 1.39 or higher is required.

# Python project setup

`pip install maturin`

# Build the package

`maturin build`

# Install the package

`maturin develop`

# Example

`python`

```
import guessing_game
guessing_game.guessing_game()
```
```bash
Type "help", "copyright", "credits" or "license" for more information.
>>> import guessing_game
>>> guessing_game.guess_the_number()
Guess the number!
Please input your guess.
30
You guessed: 30
Too small!
Please input your guess.
60
You guessed: 60
Too small!
Please input your guess.
80
You guessed: 80
Too small!
Please input your guess.
90
You guessed: 90
Too small!
Please input your guess.
100
You guessed: 100
Too big!
Please input your guess.
98
You guessed: 98
Too small!
Please input your guess.
99
You guessed: 99
You win!
```
