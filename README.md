
# Cosmic Guess

This is a Python script for a **number guessing game** with a space theme. You have to guess a secret number between 1 and 100, and the game tells you if your guess is too high, too low, or correct. You only have **7 attempts** — can you crack the cosmic code?

## 🌟 What I Learned

By building this game, I practiced and deepened my understanding of:

* **Object‑Oriented Programming (OOP)**: Structuring the game as a `CosmicGuessGame` class with methods for initialization, UI creation, game logic, and event handling.
* **Tkinter GUI Development**: Creating a full‑screen application with labels, buttons, entry fields, and dynamic feedback.
* **Event Handling**: Binding keyboard events (like pressing *Enter*) and button clicks to game functions.
* **Input Validation**: Checking user input for empty strings, non‑numeric values, and out‑of‑range numbers.
* **Game State Management**: Tracking attempts left, the secret number, and whether the game is active.
* **Visual Design**: Using a dark space‑themed color palette (`#0a0a2a` background, cyan and teal text) and custom fonts for a cohesive look.
* **User Experience (UX)**: Providing clear feedback, disabling buttons when the game ends, and offering a prominent restart option.

## 🚀 Features

* Full‑screen mode with Escape key to exit.
* Clean, space‑inspired UI with custom colors and fonts.
* Input field that accepts guesses via *Enter* key or the *Submit* button.
* Real‑time feedback with color‑coded messages (green for win, red for loss, teal/pink for hints).
* Attempts counter that updates after each guess.
* One‑click restart via the *Restart Mission* button at any time.

## 🚀 How to Play

1. Run the `cosmic_guess.py` script in Python.
2. The game will automatically start in full‑screen mode.
3. Read the instructions: *Guess a number between 1 and 100. You have 7 attempts!*
4. Type your guess in the input field and press *Enter* or click the *Submit* button.
5. The game tells you:
   * **⬆️ Too low!** if your guess is smaller than the secret number.
   * **⬇️ Too high!** if your guess is larger than the secret number.
   * **🚀 Congratulations! You guessed it!** if you win.
   * **💥 Game over! The number was X.** if you run out of attempts.
6. The *Attempts left* counter updates after every guess.
7. Click *Restart Mission* to start a new game at any time — even mid‑game!

## 🔍 Known Issues

* The game does not prevent multiple guesses if the user spams the *Submit* button very quickly.
* While input validation is in place, extremely long numbers or unusual Unicode characters might cause minor display quirks.
* The full‑screen setup (`state('zoomed')`) may behave slightly differently across operating systems (Windows, macOS, Linux).

## 🛫 Try It Yourself

1. Download the `cosmic_guess.py` file.
2. Make sure you have Python installed (3.6 or higher recommended).
3. Open a terminal or command prompt and navigate to the folder containing the script.
4. Run the script:
   ```bash
   python cosmic_guess.py
   ```
5. Enjoy the cosmic challenge!
