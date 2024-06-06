#Rock-Paper-Scissors Game

This classic game of Rock-Paper-Scissors is implemented in Python, allowing you to challenge a computer opponent and receive clear feedback on wins, losses, and ties.

Features

User-friendly gameplay: Clear instructions guide you through each round.
Fair play: The computer's choices are randomly generated.
Flexible input: Both uppercase and lowercase letters (R, P, S) are recognized for your selections.
Graceful error handling: Invalid user input is handled smoothly.
Play again option: Continue playing multiple rounds without restarting.
Platform-independent screen clearing: Uses os.system('cls' if os.name == 'nt' else 'clear') to work across operating systems.
Installation

There are no external dependencies for this project. Simply clone the repository or download the code files to get started.

Usage

Clone or Download: Clone the repository using Git or download the files directly.
Navigate: Open a terminal or command prompt and navigate to the project directory.
Run the Script: Execute the script using python <script_name>.py (replace <script_name>.py with the actual filename, e.g., python rock_paper_scissors.py).
Example Gameplay

Here's a sample of how the game unfolds:

Rock, Paper, Scissors - Shoot!

Choose your weapon [R]ock, [P]aper, or [S]cissors: r
You chose: R
I chose: P
Paper beats rock, I win!

Do you wish to play again? (Yes or No): y

Rock, Paper, Scissors - Shoot!

Choose your weapon [R]ock, [P]aper, or [S]cissors: p
You chose: P
I chose: R
Scissors beats paper! I win!

Do you wish to play again? (Yes or No): n

Thanks for playing!
