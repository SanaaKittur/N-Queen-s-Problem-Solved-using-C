# N-Queens-Problem-Solved-using-C
## About 
N Queens Problem is a famous puzzle in which n-queens are to be placed on a nxn chess board such that no two queens are in the same row, column or diagonal.
## Technique Used
* Backtracking, an algorithm which uses brute force method to find all solutions to the problem is used here.
* Backtracking uses the depth first search technique, which means when the algorithm begins to explore the solutions, the abounding function is applied so that the algorithm can determine whether the proposed solution satisfies the constraints. If it does, it will keep looking. If it does not, the branch is removed, and the algorithm returns to the previous level. 
* Here we look into placing the queens one by one in different columns, starting from the leftmost column. When we place a queen in a column, we check for clashes with already placed queens. In the current column, if we find a row for which there is no clash, we mark this row and column as part of the solution. If we do not find such a row due to clashes, then we backtrack and return false.
## Implementation
There are following functions used - **main()** function where the number of queens is taken as an input and the subsequent functions are being called; **print()** function to print the solutions based on the number of queens given as input to the problem; **place()** function for checking the conflicts while placing the positions of the individual queens. If there is no conflict found for desired position then return 1, otherwise 0; **queen()** function used for proper positioning of the queen.
## Test Cases
* Generating all possible configurations of queens on board and printing the solutions when the number of queens is equal to 4. The number of possible solutions are found to be 2.
* When the number of queens is equal to 5, the number of possible solutions are found to be 10.
* Similarly, the solutions could be generated for N number of queens.
