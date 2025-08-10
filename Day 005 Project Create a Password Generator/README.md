Project: Password Generator

## Description
This Python program generates a secure and random password based on user input.  
The user specifies how many letters, symbols, and numbers they want, and the program shuffles them to produce a strong password.

## How it works
1. The user inputs:
   - Number of **letters** (uppercase or lowercase)
   - Number of **symbols** (e.g., `!`, `#`, `$`, `%`, etc.)
   - Number of **numbers** (0–9)
2. The program:
   - Randomly selects characters from each category.
   - Combines them into a list.
   - Shuffles the list to ensure randomness.
   - Joins the characters into a final password string.
3. The password is printed to the screen.

## Features
- Uses uppercase and lowercase letters.
- Includes numbers and special symbols.
- Shuffles characters for stronger security.
- Allows fully customizable password composition.

## How to run
1. Save the file as `password_generator.py`.
2. Run the script in a terminal or IDE:
   ```bash
   python password_generator.py