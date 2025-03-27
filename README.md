# Rock, Paper, Scissors Game

A simple console-based Rock, Paper, Scissors game implemented in C++.

## Features
- Play against the computer.
- Choose between Stone, Paper, or Scissors.
- Play multiple rounds (1 to 10).
- Track game statistics, including wins, losses, and draws.
- Option to play multiple games.

## How to Play
1. The game prompts the player to enter the number of rounds (between 1 and 10).
2. In each round:
   - The player selects their choice (1: Stone, 2: Paper, 3: Scissors).
   - The computer randomly selects its choice.
   - The winner of the round is determined based on standard Rock, Paper, Scissors rules.
3. At the end of all rounds, the final game statistics are displayed.
4. The player has the option to restart the game.

## Code Structure
- `RandomNumber(int from, int to)`: Generates a random number within a given range.
- `ReadRoundNumbers(string message)`: Reads and validates the number of rounds.
- `ChoiceToString(enChoice choice)`: Converts choice enumeration to string.
- `WinnerToString(enWinner winner)`: Converts winner enumeration to string.
- `PlayerChoose()`: Allows the player to select their choice.
- `ComputerChoose()`: Generates a random choice for the computer.
- `Winner(enChoice playerChoice, enChoice computerChoice)`: Determines the winner of a round.
- `ReadRoundsInfo()`: Reads user and computer choices and determines the winner.
- `PrintRoundResults(stRoundInfo roundInfo)`: Displays the results of a round.
- `StartGame(short rounds)`: Handles game logic for multiple rounds.
- `ClearScreen()`: Clears the console screen.
- `CompleteGame()`: Runs the game and allows replaying.

## Example Gameplay
```
Enter the number of rounds (1 to 10): 3
Round [1] begins:
Enter Your choice (1: Stone, 2: Paper, 3: Scissors): 2
Player choice: Paper
Computer choice: Stone
Winner: Player

Round [2] begins:
Enter Your choice (1: Stone, 2: Paper, 3: Scissors): 3
Player choice: Scissors
Computer choice: Paper
Winner: Player

Round [3] begins:
Enter Your choice (1: Stone, 2: Paper, 3: Scissors): 1
Player choice: Stone
Computer choice: Stone
Winner: Draw

Game Over! Here are the results:
Player Wins: 2
Computer Wins: 0
Draws: 1
```

## License
This project is licensed under the MIT License.

## Author
Chiheb abiza

