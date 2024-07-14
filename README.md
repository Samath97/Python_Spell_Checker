# Python_Spell_Checker

## Overview

The Spelling Checker is a graphical user interface (GUI) application that checks and corrects the spelling of a word entered by the user. The application uses the Tkinter library for the interface and TextBlob for spelling correction.

## Features

- Check the spelling of a word.
- Display the corrected word.

## How It Works

### Main Screen

- Heading: Displays the application title "Spelling Checker".
- Text Entry: Enter the word you want to check for spelling.
- Check Button: Click to check and display the corrected word.
- Corrected Word: Displays the corrected spelling of the entered word.

## Code Explanation:

### Imported Libraries:

- tkinter: Used for the graphical user interface.
- textblob.TextBlob: Used for spelling correction.

### Function:

- check_spelling(): Fetches the entered word, corrects the spelling using TextBlob, and displays the corrected word.

### GUI Elements

- Heading: A label to display the application title.
- Text Entry: An entry widget for entering the word to be checked.
- Check Button: A button to trigger the spelling check.
- Corrected Word Label: A label to display the corrected word.

### Notes

- The application uses TextBlob's correct() method to check and correct the spelling of the entered word.

### Example

- Open the application.
- Enter "speling" in the text entry box.
- Click the "Check" button.
- The application will display "Correct text is : spelling".
