# Basic Pong HTML Game


<img width="300" alt="image" src="https://user-images.githubusercontent.com/2433219/94984423-03b57400-0509-11eb-91b0-974280cec0a2.png">



This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally as this is your challenge.

#  Prepare The challenge:

1) Open the terminal by clicking  <span style="color:yellow">**CTRL+ALT+T**</span>

2) In the command line interface navigate to Desktop folder 

    ( you don't know how to do that? It is okay, just copy and paste this into your terminal <span style="color:red">**cd Desktop**</span> to the terminal and hit <span style="color:yellow">**Enter**</span> )
3) Clone the html file repository using this command <span style="color:red">**git clone  https://github.com/HanaAbdi/pong-game/blob/main/pong.html**</span>

4) Run this commad <span style="color:red">**code pong && python3 -m http.server --directory pong**</span>

5) Now on your browser go to http://localhost:8000/ and click on <span style="color:blue">**pong.html**</span>

6) To do the challenge use your vscode to edit the pong.html file.


#  Your challenge: 

1) Change the colour of the ball.

2) Change the velocity of the ball and the speed of the paddles.

3) Change the direction of the ball to be in the opposite direction when the ball goes past a paddle.

4) *optional* Please add in the score on Pong game - so for instance each player gets a score. 

5) *optional* Add in rounds - how many rounds is each game?


## Further Exploration - if you wish.

- Score
  - When a ball goes past a paddle, the other player should score a point. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.
  
**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

