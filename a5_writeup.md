# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?
I learned a lot about stacking and what it does to the code and I learned how to connect and implemate it into the actual code. I also learne dabout breath and depth searching and how I could use them in the assignment. I faced some challenges when implementing the board class methods as I was a little confused the least constrained cells and how we get theere because I was less knowledgeable on them. When we went over it I started to understand which helped me overcome that challenge. 


2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?
I can use what I learned for problems that involve searching or making decisions, like solving puzzles or finding paths on a map. DFS could be used to explore all possible routes in a maze, and BFS could be used to find the shortest path and constraint satisfaction could help with scheduling or planning tasks.


3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?
A Stack uses LIFO which means the last item added is the first taken out. It’s used in DFS to explore one path deeply before backtracking. A Queue uses FIFO where the first item added is the first taken out. It’s used in BFS to explore all neighbors before going deeper. Using a Stack makes the search go deep first, while a Queue makes it explore level by level.