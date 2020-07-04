Assignment0 (AI Update) - 

The simplest AI change for controlling the paddles.

The changes:

1) The paddles start in the middle during every serve.

2) Keyboard control of players is removed and the new AI control is introduced.

3) The AI for player 1 keeps paddle1's y-coordinate aligned with the ball's y-coordinate.

4) The AI for player 2 uses basic straight line coordinate geometry and moves more like a human player. 

Limitations:

1) If the 'dy' of the ball exceeds the paddle speed limit the AI can't follow the ball.

2) If the 'dx' of the ball goes beyond a certain value the ball will move too fast and completely bypass the paddles between frames because of how the collision function is defined.
