# 2D breakout game using pure JavaScript.

- <a href="https://developer.mozilla.org/es/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript">Complete Tutorial</a>

- In this step-by-step tutorial we create a simple MDN Breakout game written entirely in pure JavaScript and rendered on HTML5 canvas.

- Use the HTML canvas element with either the canvas scripting API or the WebGL API to draw graphics and animations.

- Basics of using the canvas element to implement fundamental game mechanics like rendering and moving images, collision detection, control mechanisms, and winning and losing states. To get the most out of this series of articles you should already have basic to intermediate JavaScript knowledge.

## Details

1.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/create_the_canvas_and_draw_on_it">Create the Canvas and draw on it.</a>

    - Before we can start writing the game's functionality, we need to create a basic structure to render the game inside. This can be done using HTML and the canvas element.

2.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/move_the_ball">Move the ball.</a>

    - You already know how to draw a ball from working through the previous article, so now let's make it move. Technically, we will be painting the ball on the screen, clearing it and then painting it again in a slightly different position every frame to make the impression of movement — just like how movement works with the movies.

3.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/bounce_off_the_walls">Bounce off the walls.</a>

    - It is nice to see our ball moving, but it quickly disappears from the screen, limiting the fun we can have with it! To overcome that we will implement some very simple collision detection (which will be explained later in more detail) to make the ball bounce off the four edges of the Canvas.

4.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/paddle_and_keyboard_controls">Paddle and keyboard controls</a>

    - The ball is bouncing off the walls freely and you can watch it indefinitely, but currently there's no interactivity. It's not a game if you cannot control it! So let's add some user interaction: a controllable paddle.

5.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/game_over">Game over.</a>

    - It's fun to watch the ball bouncing off the walls and be able to move the paddle around, but other than that the game does nothing and doesn't have any progression or end goal. It would be good from the gameplay point of view to be able to lose. The logic behind losing in breakout is simple. If you miss the ball with the paddle and let it reach the bottom edge of the screen, then it's game over.

6.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/build_the_brick_field">Build the brick field.</a>

    - After modifying the gameplay mechanics, we are now able to lose — this is great as it means the game is finally feeling more like a game. However, it will quickly get boring if all you do is bounce the ball off the walls and the paddle. What a breakout game really needs is some bricks to destroy with the ball, and this is what we'll create now!

7.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/collision_detection">Collision detection.</a>

    - We have the bricks appearing on the screen already, but the game still isn't that interesting as the ball goes through them. We need to think about adding collision detection so it can bounce off the bricks and break them.

8.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/track_the_score_and_win">Track the score and win.</a>

    - Destroying the bricks is really cool, but to be even more awesome the game could award points for every brick a user hits, and keep count of the total score.

9.  <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/mouse_controls">Mouse controls.</a>

    - The game itself is actually finished, so let's work on polishing it up. We have already added keyboard controls, but we could easily add mouse controls too.

10. <a href="https://developer.mozilla.org/es/docs/games/tutorials/2d_breakout_game_pure_javascript/finishing_up">Finishing up.</a>

    - There's always room for improvements in any game we write. For example, we can offer more than one life to the player. They could make a mistake or two and still be able to finish the game. We could also improve our code rendering.

