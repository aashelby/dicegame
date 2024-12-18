Aaron Shelby Tuple Out Dice Game INST126 December 17, 2024

Description:

The Tuple Out Dice Game is a turn-based game for two players. Players roll three dice per turn, with the option to reroll unfixed dice to improve their score. The game includes special conditions like "tuple out," where rolling three of the same number ends the player's turn with zero points.

Features:

Two-player turn-based gameplay. Rolling and rerolling mechanics with fixed and unfixed dice. "Tuple out" condition that adds risk to rerolling. Scoring system that tracks each player's total score. Game ends when a player reaches or exceeds a target score (default is 50 points). Input validation and error handling for a smooth gaming experience.

Rules of the Game:

The objective of the game is to be the first person to reach or exceed the target score. On the initial roll, each player rolls three dice. If two dice show the same number, those dice are “fixed” and cannot be rerolled. The player may choose to reroll the unfixed dice. Players can reroll unfixed dice as many times as they like; however, any new matching dice become fixed. If all three dice show the same number at any time, the player “tuples out” and scores 0 points for that turn, and their turn is immediately over. When the player decides to stop rerolling then they score the sum of all three dice. The winner is decided by the first player to reach or exceed the target score (which is chosen by the players in the code) and wins the game.

Prerequisites:

Python installed on your system A terminal or command prompt to run the game

Installation and How to Run the Game:

Clone or Download the Repository Navigate to the Project Directory Open a terminal or command prompt On Windows, you can use Command Prompt or PowerShell On macOS or Linux, you can use Terminal Run the Game “python dicegame.py”

How to Play:

Start the Game At the start, it will display the current player’s turn and score. Rolling the Dice The game will automatically will three dice for the current player. Deciding on Rerolls If two dice have the same number, they become fixed The player will be prompted with a yes or no on whether to reroll the unfixed dice (type either yes or no) If you press enter without typing anything, the game defaults to no If you enter an invalid response, you will be prompted again Repeating Rerolls After rerolling, if there are still unfixed dice, the player can choose to reroll again. This process repeats until the player decides to stop or tuples out Ending the Turn The turn ends when the player chooses not to reroll or tuples out. The player’s score for the turn is calculated and added to their total score. Winning the Game The game continues with players alternating turns. The first player to reach or exceed the target score (default for the game is 50) wins.

Example Gameplay:

Player 1's total score: 0

Player 1's turn: Rolling 3 dice... Initial roll: [2, 5, 2] Fixed dice: [2, 2], Unfixed dice: [5] Do you want to reroll the unfixed dice? (yes/no): yes Dice after reroll: [2, 5, 2] Fixed dice: [2, 2], Unfixed dice: [5] Do you want to reroll the unfixed dice? (yes/no): no Keeping the unfixed dice as: [5] Final dice: [2, 5, 2] Total score this turn: 9 Player 1's updated score: 9

Player 2's total score: 0

Player 2's turn: Rolling 3 dice... Initial roll: [4, 4, 4] Tuple out! All dice are 4. You score 0 points this turn. Player 2's updated score: 0
