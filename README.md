# Task-1
# Hangman Game (Python)

## Overview

This project is a **simple text-based Hangman game** built using Python. The player tries to guess a hidden word **one letter at a time**. The player has **6 chances** to guess incorrect letters before the game ends.

The game randomly selects a word from a **predefined list of five words**, and the player continues guessing until either:

* The word is completely guessed, or
* The player runs out of attempts.

This project demonstrates basic Python programming concepts such as loops, conditionals, lists, strings, and the `random` module.

---

## Features

* Random word selection from a predefined list
* Letter-by-letter guessing
* Maximum of **6 incorrect guesses**
* Displays correctly guessed letters in their positions
* Tracks incorrect guesses
* Simple **console-based interaction**

---

## Technologies Used

* **Python 3**
* Standard Python libraries:

  * `random`

---

## Key Programming Concepts

This project uses the following Python concepts:

* **Lists** – to store predefined words
* **Strings** – to handle the hidden word and guesses
* **While loops** – to keep the game running until completion
* **If-else statements** – to check guesses
* **Random module** – to randomly select a word

---

## Predefined Word List

The game uses a simple list of five words:

```
["apple", "tiger", "chair", "table", "plant"]
```

---

## How the Game Works

1. The program randomly selects a word from the predefined list.
2. The word is hidden using underscores (`_ _ _ _`).
3. The player guesses **one letter at a time**.
4. If the guessed letter is correct:

   * The letter is revealed in the correct position(s).
5. If the guess is incorrect:

   * The number of remaining attempts decreases.
6. The game continues until:

   * The word is fully guessed (**player wins**), or
   * The player reaches **6 incorrect guesses** (**player loses**).

---

## How to Run the Program

### Step 1: Install Python

Ensure **Python 3** is installed on your system.

Check with:

```
python --version
```

### Step 2: Save the Program

Save the Python file as:

```
hangman.py
```

### Step 3: Run the Program

Run the game using:

```
python hangman.py
```

---

## Example Gameplay

```
Welcome to Hangman!

Word: _ _ _ _ _
Guess a letter: a

Correct guess!

Word: a _ _ _ _
Attempts left: 6

Guess a letter: z
Wrong guess!

Attempts left: 5
```

---

## Future Improvements

Possible enhancements for the project:

* Add **more words**
* Display **ASCII hangman graphics**
* Prevent **duplicate guesses**
* Add **difficulty levels**
* Create a **GUI version** using Tkinter or Pygame

---

## Author

Student Project – Hangman Game using Python.
