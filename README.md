# AI-Minesweeper
Play a game of minesweeper with the help of an AI


Run [runner.py](https://github.com/parijaat007/AI-Minesweeper/blob/master/runner.py) for seeing this project in action. The AI makes a move each time you click 'AI Move' button in the GUI. You can also make a move of your own by clicking on the individual cells in the minefield.

### Instructions for changing game metrics
The difficulty of the game can be changed by changing the values height, width and mines on lines 7, 8 and 9 of [runner.py](https://github.com/parijaat007/AI-Minesweeper/blob/master/runner.py)

All the logic for the AI is stored in [minesweeper.py](https://github.com/parijaat007/AI-Minesweeper/blob/master/minesweeper.py).

The AI only takes safe moves when possible. Otherwise it will take a random move(for example, if it is the first move or if there are absolutely no connected safe spaces.)
The game ends itself and shows the result when the are no safe spaces left.
