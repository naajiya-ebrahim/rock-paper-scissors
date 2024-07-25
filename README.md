# Rock, Paper, Scissors Game
This is a simple command-line implementation of the classic Rock, Paper, Scissors game. The player competes against the computer, which randomly selects a choice.

## Features
* Player can choose between "rock," "paper," or "scissors."
* The computer randomly selects its choice from the same options.
* The result is displayed, indicating whether the player won, lost, or tied.

## Requirements
* Python 3.x

## Usage
1. Clone or download this repository to your local machine.

2. Ensure you have Python installed on your system.

3. Run the script using Python:
  *python rock_paper_scissors.py*
4. Follow the prompt to enter your choice: "rock," "paper," or "scissors."

5. The program will display the choices made by both the player and the computer, and announce the result.

## Code Overview
### Functions:
* get_choices(): Prompts the player for a choice and randomly selects a choice for the computer. Returns a dictionary of choices.
* check_win(player, computer): Compares the player's choice with the computer's choice and determines the result. Prints the choices and returns a message indicating the outcome.

## Game Logic
* Rock beats scissors.
* Scissors beats paper.
* Paper beats rock.
* If both the player and the computer choose the same option, it's a tie.

## Customization
* Add more options to the game, for a more complex version.
* Modify the messages to personalize the game experience.
