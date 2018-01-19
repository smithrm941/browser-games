# Rhonda's Awesome Browser Games


### A collection of three games to be played in a web browser. Made with HTML, CSS, and JavaScript, including some jQuery and some vanilla JS DOM manipulation.

#### Tic Tac Toe

<img src='./TicTacToeDemoGIF.gif'/>

Two player game. Whoever clicks in a box first is "X" and the other person is "O". A winner is declared when a player has three in a row. There is also a button to start over. Game logic was created primarily using a tutorial.

#### Simon

<img src='./SimonDemoGIF.gif'/>

One player game. The computer "clicks" one of four color changing, noisemaking sections of a circle and the player has to copy the pattern. Score is revealed once the player loses by making a mistake and restarts again. Built from scratch.

#### Tetris

<img src='./TetrisDemoGIF.gif'/>

One player game. Score points for filling lines with falling blocks. More points for five lines at once! Looping Tetris theme and other sound effects. Basic game logic based on a tutorial (https://www.youtube.com/watch?time_continue=3082&v=H2aW5V46khA) but I added a scoring system based on the Game Boy Tetris scoring, including levels and speeding up the block dropping as the level increases.






Live at https://rhondasgames.herokuapp.com


To play locally:

Clone the repo, install npm dependencies, and start the server:

```shell-session
$ git clone git@github.com:smithrm941/browser-games.git
$ cd browser-games
$ npm install

...

$ npm start
...
Starting up http-server, serving ./public
Available on:
  http://127.0.0.1:4321
  http://10.0.1.11:4321

Then open `http://localhost:4321/` in your browser of choice and play away!
```
