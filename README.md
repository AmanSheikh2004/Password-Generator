# Password-Generator

This is a GUI-based password generator application built with Python's Tkinter library. The application allows users to generate secure, customizable passwords with options for including or excluding specific character types and characters. Additionally, users can easily copy generated passwords to the clipboard.

## Features

- **Password Length**: Set the desired length of the password.
- **Character Types**: Include or exclude uppercase letters, lowercase letters, digits, and symbols.
- **Exclude Characters**: Specify characters to be excluded from the generated password.
- **Clipboard Integration**: Copy the generated password to the clipboard with a single click.

## Requirements

- Python 3.x
- Tkinter (usually included with Python)
- `pyperclip` library for clipboard functionality

## Installation

1. Clone this repository or download the source code.
2. Install the `pyperclip` library using pip:
   ```sh
   pip install pyperclip

## Usage

Run the password_generator.py script:
    python password_generator.py
The GUI window will open. Use the available options to generate a password:

Set the password length.
Select the character types to include.
Optionally, enter characters to exclude from the password.
Click "Generate Password" to create a password.
Click "Copy to Clipboard" to copy the generated password.
