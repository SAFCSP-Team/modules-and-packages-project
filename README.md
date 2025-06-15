# Modules and Packages Project

### Objective
The project's main focus is to understand modules and packages in Python.

### Problem
Create a simple “Guess the Number” game using Python packages, modules, and the math and random standard libraries.

### Implementation
1. **Create the package and modules:**
    - Set up a directory structure with a `gameutils` package containing `helpers.py` and `logic.py`.
    - Directory Structure
```
guessgame/
├── main.py
└── gameutils/
    ├── __init__.py
    ├── helpers.py
    └── logic.py
```

2. **Develop helper functions in `helpers.py`:**
    - Implement `print_welcome()` to greet the player.
    - Implement `calculate_points(attempt, max_attempts)` using `math.ceil` to calculate the player’s score.
       > **Hint**: points = ceil(100 / attempt)

3. **Develop game logic in `logic.py`:**
    - Implement `generate_number()` using `random.randint` to pick a secret number.
    - Implement `check_guess(secret, guess)` to compare the guess and provide feedback.

4. **In `main.py`:**
    - Import and use functions from the custom modules.
    - Run the game loop, giving the player three chances to guess.
    - On a correct guess, use `calculate_points` to determine and display the score.
      

### Qualification to pass
- The project has the correct directory structure (gameutils package with two modules).
- All logic and helper functions are placed in the correct modules within the gameutils package.
- The game runs successfully from `main.py`, allows the player to guess a number, and provides feedback.
- The random and math modules are used correctly.
- All the functions from custom modules are imported and used in `main.py`.


### Submission
- Submit your project by sending the solution file via email.

