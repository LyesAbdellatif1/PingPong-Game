# PingPong-Game


Lab report(Abdullatif Lyes)
1.Introduction
Pong game is a two-player table tennis-themed video game. The game involves two paddles and a moving ball. The players have to move paddles in an upwards or downwards direction and save the ball from getting hit onto the wall. If the ball hits the wall then it’s a score for another player.In our case we will have just one player .


2.Problem Statement
Task:Try to do the steps of the tutorial. Create Pong game .
send  an archive with the project ( Pong Game ) .

3.User Guide
How to play the game
Instructions to get to the game:
Launch the program
Click the Play button
The game should start once you've clicked play
Instructions for the game itself:
Mouse movement moves the player paddle
The ball will first move towards the computer's paddle
The computer's paddle will hit the ball towards the user's half of the form
If the player manages to hit the ball with their paddle, the ball will bounce back towards the computer's half of the form
If the player misses the ball then they have lost and can either exit the game with the X button or restart the game with the Plays button


4.Programmer's Guide
Procedure:
Create an HTML file with the name index.html.
Create a CSS file with the name styles.css and link it in the index.html file using the link tag.
Create a JS file with the name index.js and link it in the index.html file using a script tag.
Create a div for the game board, ball, and 1 divs for paddles, i.e. player-1 and player-2.
Give some style to your game in the CSS file.
Get a reference to paddles, balls, and game boards in JS.
Create a function in the index.js file with the name move ball.
Give the ball a random direction and a random speed by changing the x and y coordinates of the ball.
Apply collision with ball and game board’s top/bottom side, i.e. if the ball touches the top/bottom of the board then multiply -1 * y velocity of the ball.
Apply collision with ball and game left and right side of the game board.
Apply collision with ball and paddles. i.e. multiply -1 * x velocity of the ball.

