# Tic-Tac-Toe ❎⭕
Tic Tac Toe game created using opengl.

## Introduction 😀
<b>OpenGL</b> is the premier environment for developing portable, interactive 2D and 3D graphics applications. OpenGL fosters innovation and speeds application development by incorporating a broad set of rendering, texture mapping, special effects, and other powerful visualization functions 
Tic tac toe game is very popular and fairly simple to play. In this there is a board with 3x3 boxes. The goal is to be one of the players to fill same symbols in 3 boxes either horizontally, vertically or diagonally in the grid. 
Here I have created a tic tac toe game with animation using opengl features and functions.
I have included player 1 as human and player 2 as computer. 

## Computer Graphics Concepts Used 📖
1. Drawing lines – Using GL_LINES. This is argument in begin function iteratively draws points between the vertex passed inside function.
2. Drawing quadratic objects using pointer.
3. Setting up display callback for the current window using glutDisplayFunc() and that of viewport size by using glViewport function.
4. Transformation functions. <br>
      •	Translation – 
          If one has a linear transformation T(x) in functional form, it is easy to determine the transformation matrix A by simply transforming each of the vectors of the standard basis by T and then inserting the results into the columns of a matrix.

      •	Rotation –
          For rotation by an angle θ anticlockwise about the origin, the functional form is x' = xcosθ − ysinθ and y' = xsinθ + ycosθ.

      •	Scaling –
          For scaling (that is, enlarging or shrinking), we have x’=(sx).x ans y’=(sy).y .
5. Changing Viewmode – By setting up and loading matixmode.
 
## User Defined Functions ➗

###	• init_game()
      Used to initialize our game and set up game variables.
### • check_move()
      Check if a win sequence has occurred or not. Returns 1 if there is a winner.
### • computer_move()
      Sets up the next computer move if the game is not drawn or won yet. It works in three steps in which each step calls a user defined function:
### • blocking_win() 
      It is to determine if there are any moves that the user can play in the next turn to win and if it exists, then computer will block that and play in that square and return 1 and if it doesn’t exist, return 0.
### • check_corner() 
      If first function return 0 then function is called. It will look for the vacant corners and play on that square if found and return 1 and if not found, return 0.
### • check_row() 
      If second step returns 0 then function is called. It will look for all the remaining boxes and fill any if found vacant.
      
## Don't forget to Star the repo if found useful 🌟


