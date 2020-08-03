# 8-Queen-Problem

This problem is to find an arrangement of 8 queens on a chess board, such that no queen can attack any other queens on the board. The chess queens can attack in any direction as horizontal, vertical, horizontal and diagonal way. A binary matrix is used to display the positions of N Queens, where no queens can attack other queens. The eight queens puzzle is an example of the more general n queens problem of placing n non-attacking queens on an n×n chessboard.

State: 8 states are taken to describe the positioning of queens on the chess board.Each state represent the row where queens would be placed

Intitial state: All the boxes is initialize with value 0.

Action : Queen placed on (i,j) such that ith row and jth column should not have any other queen on board and (i-1,j-1),(i-1,j+1),(i+1,j-1),(i+1,j+1) should not have any queen i.e adjacent diagonal box.

Goal state: There are 92 possible distinct possible solution,some of them would look like same as they would differ in rotation of some of the solution. One of the goal state is ........

1 0 0 0 0 0 0 0

0 0 0 0 1 0 0 0

0 0 0 0 0 0 0 1

0 0 0 0 0 1 0 0

0 0 1 0 0 0 0 0

0 0 0 0 0 0 1 0

0 1 0 0 0 0 0 0

0 0 0 1 0 0 0 0
