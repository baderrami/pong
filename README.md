# pong
Simple pong game using java 2D inspired by youtube tutorials. 
https://www.youtube.com/watch?v=MPJ8XRpZZCk&ab_channel=CodingHeaven

The game consists of 6 very short and intuitive classes:
•Game.java: handles the rendering and physics updating using a
separate thread. It contains all the objects. This class extends
Canvas to draw and implements Runnable to run the game loop.
•Window.java: handles the JFrame and adds the Game Canvas into it.
•Ball.java: contains the properties for the ball that bounces around.
•Paddle.java: contains the properties for both paddles.
•KeyInput.java: handles the key input in a clever way to avoid the
paddles from bugging when the direction changes.
•MainMenu.java: displays a main menu at the start of the game.
Controls:
•Up and Down arrow keys for Red player (Right Player).
•W and S keys for Green player (Left Player).

