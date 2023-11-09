# Dictionary APP

## Overview

The Dictionary APP is a simple command-line tool that allows users to look up the definitions of words. It uses a JSON data file that contains a list of words and their corresponding definitions. Users can enter a word, and the script will provide the word's definition.

The script is designed to handle various input cases, including case-insensitive queries and suggestions for similar words when an exact match is not found.

## Features

- **Word Lookup**: Users can input a word to get its definition.

- **Case-Insensitive Search**: The script handles case-insensitive word lookup.

- **Close Matches**: The script suggests close matches when an exact match is not found.

## How to Use

1. Make sure you have Python installed on your system.

2. Download the "data.json" file and ensure it's in the same directory as your script.

3. Run the script by executing `python app1.py` in the terminal.

4. Enter the word you want to look up when prompted.

5. The script will provide the word's definition if found, or suggest close matches if no exact match is found.

## Example Usage

Here's how to use the script:

$ python dictionary.py
Enter word: apple

The round fruit of a tree of the rose family, which typically has thin red or green skin and crisp flesh.
Used in names of unrelated fruits or other plant products that resemble apples in some way, e.g., custard apple.
The tree that bears the apple.
A tree of a genus that includes the apple.
$ python dictionary.py
Enter word: applee
Did you mean apple instead? Enter Y if yes, or N if no: Y
The round fruit of a tree of the rose family, which typically has thin red or green skin and crisp flesh.

## Notes

- The "data.json" file should follow the specified format with words as keys and definitions as values. You can expand and customize this file to include more words and definitions.

- The script is case-insensitive, so you can enter words in any case.

- When a word is not found, the script suggests close matches and allows the user to confirm the intended word.

- The script is a simple tool for word lookup but can be enhanced with additional features or integrated into other applications.

Explore the world of words with the Dictionary APP, a handy tool for finding word definitions quickly and easily.

## License

This project is licensed under the MIT License. You are free to use and modify the code for your own purposes.
