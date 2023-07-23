# Exercise

##Exercise: ft_sudoku_solver
Allowed functions : malloc

- Create a function that takes a 9x9 array representing a sudoku puzzle and solves it.
- The array will contain digits from 1 to 9 in the known spots, and zeroes in the unknown spots.
- The function must, through a suitable algorithm (like backtracking) find a suitable solution, if one exists.
- If several solutions exist, the function must return the lexicographically smallest solution (first row, then columns).
- Here's the array to be used:
```int grid[9][9] = {
{5, 3, 0, 0, 7, 0, 0, 0, 0},
{6, 0, 0, 1, 9, 5, 0, 0, 0},
{0, 9, 8, 0, 0, 0, 0, 6, 0},
{8, 0, 0, 0, 6, 0, 0, 0, 3},
{4, 0, 0, 8, 0, 3, 0, 0, 1},
{7, 0, 0, 0, 2, 0, 0, 0, 6},
{0, 6, 0, 0, 0, 0, 2, 8, 0},
{0, 0, 0, 4, 1, 9, 0, 0, 5},
{0, 0, 0, 0, 8, 0, 0, 7, 9}};
```
-Here’s how it should be prototyped: `int **ft_sudoku_solver(int grid[9][9]);`
# Submissions 
 git push your solution in this repo and hit /submit in Discord