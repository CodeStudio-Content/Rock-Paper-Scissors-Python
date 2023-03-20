<h1 align="center"> Rock Paper Scissors </h1>

| ![Screencast from 05-03-23 03_09_13 PM IST](https://user-images.githubusercontent.com/77020164/222953096-413f478e-3d1f-4d0a-b78b-eb9f26780f96.gif) | ![Screencast from 05-03-23 03_09_34 PM IST](https://user-images.githubusercontent.com/77020164/222953091-8bc2066b-9394-4fcf-a5cc-5b76aa7fdd02.gif) 
|-|-|



## About
The game is played by two players, each making one of three hand gestures: "rock" (closed fist), "paper" (flat hand), and "scissors" (V-shape with index and middle fingers). There are only three possible outcomes besides a tie: rock beats scissors, paper beats rock, and scissors beat paper. If both players make the same gesture, the game is tied and usually replayed to break the tie.

## Requirements

1. Python 3.x
2. Tkinter library (which is usually included with Python)

## Getting Started

* Clone this repository to your local machine.
* Open a terminal window and navigate to the cloned repository.
* Run the following command to start the game: python game.py

## How to Play

1. The game is played against the computer.
2. The player selects one of three hand gestures: "rock", "paper", or "scissors".
3. The computer generates a random choice.
4. The game determines the winner based on the rules of the game.
5. The game is played for five rounds, with the winner being the player or computer with the most wins at the end of the game.


## Blog

Check out our project blog post for more information on the development process and our thoughts on the Rock Paper Scissors project:

* [Rock Paper Scissors using Python](https://www.codingninjas.com/codestudio/library/rock-paper-scissors-game-in-python?utm_source=github&utm_medium=organic&utm_campaign=blog-rock-paper-scissors-game-in-python)

## Code Structure

### The code is organized into the following functions:

- `generate_computer_choice()` : This function generates a random choice for the computer.
- `determine_winner(player_choice, computer_choice)` : This function determines the winner of each round based on the player's and computer's choices.
- `play_game(player_choice, player_name)` : This function starts a new game, takes in the player's choice and name, generates a computer choice, determines the winner, updates the scores and labels, and checks if the game has ended.
- `restart_game()` : This function restarts the game after it has ended, resetting the scores and rounds played, updating the labels to reflect the new game, and enabling the buttons to play again.
- `get_player_name()` : This function gets the player's name by creating a new window using the `Toplevel()` function, asking the player to enter their name, and updating the labels.

### The code also defines the following labels and buttons for the game:

- `player_score_label` : This label displays the player's score.
- `computer_score_label` : This label displays the computer's score.
- `player_result_label` : This label displays the player's choice.
- `computer_result_label` : This label displays the computer's choice.
- `winner_label` : This label displays the winner of the game.
- `rock_button` : This button allows the player to select "rock".
- `paper_button` : This button allows the player to select "paper".
- `scissors_button` : This button allows the player to select "scissors".
- `play_again_button` : This button allows the player to play the game again after it has ended.
- `rounds_label` : This label displays the current round number.



<div align="center">
  
## Made with ❤️ , Python, and Tkinter. Enjoy!
  
</div>
