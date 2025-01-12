# Kropki Sudoku Solver 🔢🟡⚫
This project is a specialized solver for Kropki Sudoku, an advanced variant of traditional Sudoku that incorporates additional constraints using white and black dots. The solver automates the process of finding valid solutions, ensuring all Kropki rules are satisfied.

Features
	•	Kropki Constraints: Handles both white dots (indicating consecutive numbers) and black dots (indicating numbers with a ratio of 2:1).
	•	Dynamic Validation: Ensures that all Kropki rules are followed during solution generation.
	•	Efficient Backtracking: Implements a backtracking algorithm optimized for Sudoku puzzles with extra constraints.
	•	Visualization: Provides a clear representation of the Sudoku grid and the applied constraints.
	•	Customizable Grid Sizes: Supports both traditional 9x9 Sudoku and extended grid formats.

Technologies Used
	•	Python 🐍
	•	NumPy for grid manipulation
	•	Matplotlib for visualizing Sudoku solutions
	•	Jupyter Notebook for interactive exploration and debugging

How It Works
	1.	Puzzle Input: Define the Kropki Sudoku grid with initial values and constraints (white and black dots).
	2.	Constraint Validation: Check the consistency of added constraints during the solving process.
	3.	Backtracking Algorithm: Efficiently explore potential solutions by filling in cells and backtracking when conflicts arise.
	4.	Solution Output: Display the completed Sudoku grid with all constraints respected.

Usage
	1.	Clone the repository
 	2.	Open the kropki_sudoku_solver.ipynb file in Jupyter Notebook.
	3.	Follow the notebook’s steps to input constraints, solve the puzzle, and visualize the solution.

Future Enhancements
	•	Add support for more complex Sudoku variants with combined constraints.
	•	Develop a user-friendly web app or GUI for solving puzzles interactively.
	•	Incorporate heuristic-based approaches to improve solver efficiency.

Acknowledgments
	•	Inspired by the unique challenges of Kropki Sudoku, which combine logic, mathematics, and pattern recognition.
	•	Thanks to open-source Python libraries and my Professor for providing guidance and inspiration.
