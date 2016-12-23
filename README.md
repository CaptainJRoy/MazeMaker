# MazeMaker
Random created maze (made in js with p5 library)

I made this algorithm with the help of a video i saw.
It's sole purpose is to generate random mazes, nothing else.
To implement it i used the "Recursive Backtracker" algorithm, wich is the following:

Recursive backtracker
The depth-first search algorithm of maze generation is frequently implemented using backtracking:
1 - Make the initial cell the current cell and mark it as visited
2 - While there are unvisited cells
    1 - If the current cell has any neighbours which have not been visited
        1 - Choose randomly one of the unvisited neighbours
        2 - Push the current cell to the stack
        3 - Remove the wall between the current cell and the chosen cell
        4 - Make the chosen cell the current cell and mark it as visited
    2 - Else if stack is not empty
        1 - Pop a cell from the stack
        2 - Make it the current cell
        
This algorithm is easily found online, the description above was copy from Wikipedia on December 23rd 2016
[https://en.wikipedia.org/wiki/Maze_generation_algorithm]


I hope that this might come in handy.