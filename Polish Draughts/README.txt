POLISH DRAUGHTS

In this project, we wanted and tried to write all the code as a single python file, except for the following tasks. We have written
this code with a different method apart from the following tasks. When we run the code, you will see that the game runs correctly.
If we were to explain the code, first we made the main screen of the game, then we organized each cell and most scenarios
one by one in commands. We tried to write these scenarios one by one with the if and else commands. According to the final scenario of the game,
we added a picture according to the winning color and added a winning sound effect. Although we have done it with a slightly different 
method according to the tasks below, we think that we have created a correct game by arranging many scenarios. When we run the game, you will see
that we have a very fluent game.


Story 
Your best friend Tom is board games lover, and he plays checkers all the time like a pro. Recently, he  is really into digital versions of his favorite games, but unfortunately he cannot find any  implementation of the Polish Draughts. 
Give Tom your console version of this game. 
In this project, your job is to implement a variation of Polish draughts for two players. You also can try  writing some AI to play the game. 
Tasks 
➢ Board 
o There is a Board class that represents the square board of Polish draughts. o There is an n parameter in the constructor that specifies the side length of the square.  The size must be an integer between 10 and 20. It is provided as user input. 
o There is a Pawn[][] fields 2D array that represents fields on a board. Each field can be  null (empty) or a Pawn instance. 
o Pawns are created and placed on every other field when the board is initialized. Their  number is determined by board size, as a 2 * n. 
o There is a print_board() method that marks rows as numbers and columns as letters. o There is a remove_pawn() method that removes pawns from the specified position. o There is a move_pawn() method that moves pawns from a specified position to  another field. 
➢ Pawn 
o There is a Pawn class. 
o There is a Color get_color() method that returns the color of the pawn(white or black). o There is a field of the Coordinates position class that represents pawn coordinates on  a board. The Coordinates class has two fields, Integer x and Integer y. 
o [Extra] There is boolean is_crowned field that returns true if a pawn is crowned. o The Pawn class contains a method that validates the move (whether it is within the  game rules) before it is performed. 
o [Extra] The Pawn class can check if the pawn can make multiple jumps according to  the rules. 
➢ Game 
o There is a Game class that contains all game logic and actions. 
o There is a start() method that starts game between players. 
o There is a method play_round() that determines one-round actions that is, checks  which player is next and whether there is a winner.
o There is a method that checks if the starting position from user input is a valid pawn  and if the ending position is within board boundaries. If so, it calls  try_to_make_move() on pawn instance. 
o There is a check_for_winner() method that checks whether there is a winner after each  round. 
o The check_for_winner() method also checks for draws. 

When we examine the code, you will see that apart from these tasks, we have created the game in a unique style.

Ali Riza Ercan
Erhan Guzelsari