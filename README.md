## Working:

-	Every time this Script is executed, a Random Solvable board is created.
-	Now, the user can first try to attempt solving it by clicking on the cells and entering values manually. Check the Input Section for the same.
-	Once the the user finalizes that the inputted number is the correct entry, pressing the enter key will attempt to input the number onto the board. 
-	Correct answers will be permanently displayed while incorrect answers will be removed. 
-	Likewise, values can be removed by pressing on the backspace or delete keys.

<p align="center">
	<img src="https://github.com/dhhruv/Sudoku-Solver/blob/master/assets/Entering%20Values.gif">
</p>

-	If at any point the player decides to solve the board, the Spacebar key can be pressed.
-	This will commence a visual which will demonstrate how the backtracking algorithm works and how it is being applied in order to solve the board.

<p align="center">
	<img src="https://github.com/dhhruv/Sudoku-Solver/blob/master/assets/Visualizer.gif">
</p>

## Input:

| Keys              | Actions                                                         |
|-------------------|-----------------------------------------------------------------|
| `Left Click`      | Selects the Box to enter a value into that cell.                |
| `Enter`           | Confirms the Value written on the board.     |
| `Backspace/Delete`| Deletes the value in that cell.                                 |
| `Space`           | Solves the Board using the Algorithm.                           |
| `h`               | Gives a Hint. Displays a random correct value on the board.     |

## Requirements:
In order to run the Script, the require **Python & PyGame** and you can install the requirements using:
```
pip install -r requirements.txt
```

## Execution:
-	Clone this repository using
```
git clone https://github.com/dhhruv/Sudoku-Solver.git
```
**OR**
Zip Download the Repository and Extract it's contents.
-	Now run the [SudokuGUI](https://github.com/dhhruv/Sudoku-Solver/blob/master/SudokuGUI.py) file directly in your Terminal using
```
python SudokuGUI.py
```
**OR**
```
python3 SudokuGUI.py
```

<p align='center'><b>Made with ❤ by Vivek Kumar</b></p>
# Sudoku-Solver
