# TicTacToe-Game-App
<p align="center">
        <img width="460" height="500"   src="https://user-images.githubusercontent.com/89569367/175859200-93fa341d-89c2-4da5-9a39-cc9d87f2e039.png">
</p>

### OBJECTIVE:
This project aims to develop a Tic Tac Toe game using Java and Andriod Studio. It mainly consists of developing and implementing a computer program where two players can play Tic Tac Toe against eachother.<br/> o develop a Tic Tac Toe game using java. It mainly consists of developing and implementing a computer program where two players can play Tic Tac Toe against eachother.<br/>

In order to understand what Tic Tac Toe game is and how to play the game, below is the description.



### GAME DESCRIPTION:

Tic Tac Toe is a two-player game (one of them being played by computer or human). In this game, there is a board with 3 x 3 squares.<br/>


<p align="center">
        <img width="460" height="600"   src="https://user-images.githubusercontent.com/89569367/175861279-7aaae603-b5f2-40b8-ae4a-2357a1f8a70c.jpg">
</p>


The two players take turns putting marks on a 3x3 board. The goal of Tic Tac Toe game is to be one of the players to get three same symbols in a row - horizontally, vertically or diagonally on a 3 x 3 grid.  The player who first gets 3 of his/her symbols (marks) in a row - vertically, horizontally, or diagonally wins the game, and the other loses the game. 

The game can be played by two players.



### GAME RULES:

A player can choose between two symbols with his opponent, usual game uses “X” and “O”.

<p align="center">
        <img width="560" height="400"   src="https://user-images.githubusercontent.com/89569367/175860112-b157f59a-7c8f-4904-a1ad-f5d126044b2b.png">
</p>




1.	The player that gets to play first will get the "X" mark (we call him/her player 1) and the player that gets to play second will get the "O" mark (we call him/her player 2).



2.	Player 1 and 2 take turns making moves with Player 1 playing mark “X” and Player 2 playing mark “O”.



3.	A player marks any of the 3x3 squares with his mark (“X” or “O”) and their aim is to create a straight line horizontally, vertically or diagonally with two intensions:<br/>

a.	One of the players gets three of his/her marks in a row (vertically, horizontally, or diagonally) i.e. that player wins the game.<br/>

b.	If no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a  draw/tie.



### IMPLEMENTATION PLAN:

The implementation workflow for this project is as follows:





Defined game rules and description.



First the game will start with empty board.<br/>







Then Player 1 will make his/her move by playing mark “X” on this board. Then Player 2 will make his/her move by playing mark “O” on this board. This will keep on continuing until the board is full of marks.



Then the program will check if Player 1 with “X” wins or Player 2 with “O” wins and that scenario will be follows: (could be vertically, horizontally or diagonally).  







If none of the players win, the program will check for draw.


<p align="center">
        <img width="560" height="600"   src="https://i.stack.imgur.com/gGJEY.png">
</p>



All this decision making is done by using Minimax algorithm.




#### Explanation with Example
In order to understand what Tic Tac Toe game is and how to play the game, below is the description.

### GAME DESCRIPTION:
Tic Tac Toe is a two-player game (one of them being played by computer or human). In this game, there is a board with 3 x 3 squares.<br/>

The two players take turns putting marks on a 3x3 board. The goal of Tic Tac Toe game is to be one of the players to get three same symbols in a row - horizontally, vertically or diagonally on a 3 x 3 grid.  The player who first gets 3 of his/her symbols (marks) in a row - vertically, horizontally, or diagonally wins the game, and the other loses the game. 


### GAME RULES:
A player can choose between two symbols with his opponent, usual game uses “X” and “O”. 
1.	The player that gets to play first will get the "X" mark (we call him/her player 1) and the player that gets to play second will get the "O" mark (we call him/her player 2).

2.	Player 1 and 2 take turns making moves with Player 1 playing mark “X” and Player 2 playing mark “O”.

3.	A player marks any of the 3x3 squares with his mark (“X” or “O”) and their aim is to create a straight line horizontally, vertically or diagonally with two intensions:<br/>
a.	One of the players gets three of his/her marks in a row (vertically, horizontally, or diagonally) i.e. that player wins the game.<br/>
b.	If no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a  draw/tie.


<p align="center">
       <img width="560" height="600"   src="https://user-images.githubusercontent.com/89569367/175860935-7ffd8914-dabc-4ddc-b57c-01c09ac53c47.gif">
</p>

### IMPLEMENTATION PLAN:
The implementation workflow for this project is as follows:


In order to visualize the defined game rules and description, the game is shown in Figures below.

First the game will start with empty board.<br/>
<p align="center">
        <img width="560" height="600"   src="https://upload.wikimedia.org/wikipedia/commons/6/64/Tic-tac-toe.png">
</p>


Then Player 1 will make his/her move by playing mark “X” on this board. Then Player 2 will make his/her move by playing mark “O” on this board. This will keep on continuing until the board is full of marks.

Then the program will check if Player 1 with “X” wins or Player 2 with “O” wins and that scenario will be follows: (could be vertically, horizontally or diagonally).  



If none of the players win, the program will check for draw.

The winner is the first player to get three of the same symbols in a row (could be vertically, horizontally or diagonally).
![image](https://user-images.githubusercontent.com/104670713/170813422-f9605ca5-ae1b-48b3-94b4-7124351f80a6.png)



