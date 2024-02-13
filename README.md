# Wordle

## Description
This script is a bash-based word guessing game inspired by the classic "Hangman" game. Players are prompted to guess a five-letter word within a limited number of attempts. After each guess, the game indicates which letters are correctly placed, which letters are in the word but in a different position, and which letters are not in the word at all.

## Dependencies
To run this script, you need:
- Bash shell (commonly available on Linux and macOS)
- `curl` utility to download the word list

## How to Run
Follow these steps to run the game:

1. Download the script and save it as a file, for example, `word_game.sh`.
2. Open a terminal and navigate to the directory where the script file is located.
3. Make the script file executable with the command:
   ```bash
   chmod +x wordle.sh
   ```

Run the game using the command:
   ```bash
   ./wordle.sh
   ```

To play with an unlimited number of guesses, run the script with the unlimit parameter:
   ```bash
   ./wordle.sh unlimit
   ```

## Gameplay Instructions
- You will be prompted to enter a five-letter word.
- If you guess a letter in the correct position, it will be highlighted in green.
- If a letter is in the word but in a different position, it will be highlighted in yellow.
- Letters not in the word will be shown in gray.
- The game continues until you guess the word or run out of attempts.

## Example
   ```mathematica
   Enter your guess (1 / 6):
   HELLO
   H  E  L  L  O      [ABCFG...XYZ]
   ```
