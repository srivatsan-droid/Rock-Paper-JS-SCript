# Rock, Paper, Scissors Game

This is a simple web-based **Rock, Paper, Scissors** game implemented using plain HTML and JavaScript. The game plays 5 rounds between a human player and the computer, then declares the overall winner based on the score.

## Features
- Play 5 rounds of Rock, Paper, Scissors.
- Human player can input their choice via a prompt.
- Computer choice is randomly generated.
- Game compares the choices and announces the winner for each round.
- Final score is displayed, and the overall winner is declared.

## How to Play
1. Open the `index.html` file in any modern browser.
2. The game will prompt you to enter your choice: **Rock**, **Paper**, or **Scissors**.
3. The computer will randomly select its choice.
4. After each round, the result of that round is displayed in the console:
   - **Human wins**: if your choice beats the computer's choice.
   - **Computer wins**: if the computer's choice beats your choice.
   - **It's a tie**: if both choose the same option.
5. After 5 rounds, the final score is displayed in the console, along with the overall winner.

## Game Rules
- **Rock** beats **Scissors**.
- **Paper** beats **Rock**.
- **Scissors** beat **Paper**.
- If both players choose the same option, it's a tie.

## Code Structure
- `getComputerChoice()`: Generates a random choice (Rock, Paper, or Scissors) for the computer.
- `getHumanChoice()`: Prompts the human player for their choice and ensures it's valid.
- `playRound(humanChoice, computerChoice)`: Plays a single round, compares the human and computer choices, and returns the result.
- `playGame()`: Plays 5 rounds, keeps track of the scores, and declares the final winner.

## How to Run the Code
1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Open the browser's **Developer Console** to see the round-by-round results and the final score.

## Example Output (in Console)
