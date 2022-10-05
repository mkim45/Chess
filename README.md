# Chess
A C++ project for final coursework that allows for a two-player simplified game of chess adhering to most standard rules. The project was completed in June 2022 and consists of an interactive GUI using a Model-View-Controller architectural pattern. Gameplay consists of standard pieces on an 8 x 8 board with alternating moves. All functionalities of possible move sets are allowed for all pieces (except for castling and promotions [automatically promotes to queen]). Gameplay ends when checkmate or draw is detected and occurs. 

The .zip file contains all files of the project, including .png files of pieces used and relevant code files. The purposes of each code files have been described below:

view.cxx and view.hxx - contains sprites, functions, and board layout that is shown to user and displays changes accordingly.
  
position_set.cxx and position_set.hxx - contains Position_set class (an efficient set of ge211:Posn variables used)

player.cxx and player.hxx - contains Player class (attribute of dark or light to determine player pieces)

piece.cxx and piece.hxx - contains Piece class (attribute of pawn, knight, bishop, rook, queen, or king for pieces)

move.cxx and move.hxx - contains details on Move (the original position and position to be moved to) utilized in gameplay from user inputs

model.cxx and model.hxx - contains Model class (details how gameplay should work, rules, movement of pieces, interaction of pieces, setup of board, and how gameplay and moves should end)

controller.cxx and controller.hxx - controls detection of user inputs of mouse clicks and mouse movements

board.cxx and board.hxx - contains Board class (details board layout, pieces for each player in the game, and positions of pieces in the game)

chess.cxx - allows the game to begin by calling the run() function from Controller

board_test.cxx - tests for edge cases and ensures Board class is functioning as intended

model_test.cxx - tests for edge cases and ensures Model class is functioning as intended (tests gameplay rules)

move_test.cxx - tests for edge cases and ensures Move is functioning as intended

player_test.cxx - tests for edge cases and ensures Player class is functioning as intended

position_set_test.cxx - tests for edge cases and ensures Position_set class is functioning as intended
