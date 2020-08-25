# Degrees-of-separation-AI
AI Search that

## About
About two years ago, when I had just started learning Python, I wrote a tic-tac-toe game [Collins1738/Tic-Tac-Toe](https://github.com/Collins1738/Tic-Tac-Toe), which was really huge for me. Now I have taken a big step further and written an Artificial Intelligence (AI) software to optimally play tic-tac-toe.

## Description
This AI is able to find the optimal next move in any position in a tic-tac-toe game
making it entirely unbeatable.
The AI when playing against humans would either draw or capitalize on a bad move made by the human, and win the game.
It's main focus is to play the best move that would make sure it never loses, and wins when bad moves are played by opposing player.

## Minimax
This AI implements Minimax 
Minimax is a decision making strategy where the AI makes a choice based on the opponent best choice.
The AI finds an optimal choice by recursively finding the opponents optimal choice if it were to make an optimal choice based on the opponent making an optimal choice...that is based on the AI's optimal choice...(and that is how the recursive pattern is formed)
It finds the minimum of the maximum choices made by the opposing player
A score is used to rank the choices; a low score signifying a good move for the AI and a high score signifying a good move for the opposing player

## TODO:
### Optimal, and fastest
Currently, when a bad move is played by the human, the AI plays any move that would lead it to win the game.
Sometimes though, the move would make the AI win the game in 2 moves instead of winning the game immediately. Winning is assured but the faster win isn't taken into account.
I plan on adding a secondary score that ranks faster wins over slower wins to allow the AI to play the optimal AND FASTER winning move!

## Installing 
Run pip3 install -r requirements.txt to install the required Python package (pygame) for the project. Then run Python3 runner.py to start the game

