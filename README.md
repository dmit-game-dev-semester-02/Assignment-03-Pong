# Assignment-03-Pong
 
Finish Pong.

1.  **(5 marks) Add states to the game.** 

    The player should see a start screen, then play the game, then a game over screen that gives them the option to play again.  

    The game states could be START, INITIALIZING, SERVING, PLAYING, GAMEOVER. 

    The game states should be used in both Update() and Draw().

2.  **(5 marks) Make actual Pong.**

    Add another paddle to the other side, controlled by different keys.  

    In implementing this, reuse the Paddle class (do NOT write another class).  

    When the ball hits either side, it should exit the screen and the game should end.

3.  **(4 marks) Add a HUD to the game.**

    It tracks and displays many times each paddle has hit the ball. 

    It displays the high score for the session. 

4.  **(3 marks) Create a new class called "Blocker".**

    It contains the standard Initialize, LoadContent, Update, and Draw methods. 

    It is instantiated from within the Pong game, and placed in the middle of the game play area.  

    It will draw itself (a coloured rectangle) and the ball will bounce off of it. 

5.  **(1 mark -- challenge!) Make the blocker object move up and down, changing directions when it hits the top or the bottom of the game play area.** 

6.  **(1 mark -- challenge!) Make the paddle turn a different colour for 500 milliseconds when they are touched by the ball.**