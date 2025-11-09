# 🪓 Python Command-Line Hangman Game

This is a fun, text-based implementation of the traditional Hangman word game, built using core Python features.

## ✨ Key Features
* **Dynamic Word Selection:** The game selects a random word from an extensive list imported from `words.py`.
* **Lives System:** Players start with **7 lives** and lose one for every incorrect letter guess.
* **Visual Feedback:** The hanging man's progress is displayed using **ASCII art** (defined in `hangman_visual.py`) which updates after every wrong guess.
* **Input Validation:** The game checks if the user has already guessed a letter or if the input is a valid letter.

## ⚙️ Project Structure
The game is split into three Python modules for clean organization:

1.  **`Hangman.py`**:
    * The main executable script.
    * Contains the core game loop (`hangman()`) which handles user input, updates the word display, manages the list of used letters (`used_letters`), and checks for win/loss conditions.
    * Imports words from `words.py` and visuals from `hangman_visual.py`.
2.  **`words.py`**:
    * A large list of English words that the game randomly selects from.
3.  **`hangman_visual.py`**:
    * A dictionary (`lives_visual_dict`) that maps the number of remaining lives to the corresponding multi-line string (ASCII art) to display the hangman visually.

## 🚀 How to Run the Game

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Python-Command-Line-Hangman.git](https://github.com/YourUsername/Python-Command-Line-Hangman.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Python-Command-Line-Hangman
    ```
3.  **Run the main script:**
    ```bash
    python Hangman.py
    ```

## 🎮 Gameplay Example
