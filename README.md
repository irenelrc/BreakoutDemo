# BreakoutDemo

A game writen in Java. A school project of CS349 University of Waterloo Summer 2019.

The repository only shows the demo UI. The source code is set private to prevent plagiarism, please contact me if you want to see the code. :)

### /******************** Input ********************/

First argument -- FPS: valid input 25 - 50

- if < 25, will be set to 25
   
- if > 50, will be set to 50

Second argument -- Speed: valid input 1(Super low), 2(Low), 3(Med), 4(High), 5(Super high). Other values will be automatically set to 3(Med)


### /******************** How to Run ********************/

type "gradle build"<br/>

type "gradle run --args='someValidFPSValue someValidSpeedValue'


### /******************** How to Play ********************/

A -- Move panel left

D -- Move panel right

ESC -- Exit the game

L -- Cheating

K -- Turn off cheating

Move mouse Left/Right -- Move panel left/right


### /******************** Score ********************/

From bottom to top, every brick in i level get 2i - 1 score.

For example: The lowest level (purple brick) get 1 score, the second lowest level (blue brick) get 3 score, etc.


### /******************** Additional Feature ********************/

There are three levels:

In level 1, every brick will disappear when hit once.

In level 2, every brick will disappear when hit twice.

In level 3, every brick will disappear when hit three times!



### /******************** Interface ********************/

Splashscreen:

- You can read the instruction and then click "START GAME" to start the game.
  
Playingscreen:

- The above part is the information, including current score, current level, chosen fps, and chosen speed.
  
- The below part is the game view.
  
Resize:

- You can resize the screen whenever you want, the ball / paddle / brick will be resized as well.
  
- Ball will stop for a while waiting for you to finish resizing.


### /******************** If you are a terrible player :( ********************/

Use Key "L" to extend the paddle to the longest! So that ball will never fall!

Use Key "K" to turn off cheating if you want to play by yourself.


### /******************** Resources Reference ********************/

Font Reference: http://typodermicfonts.com/karma/


### /******************** Other information ********************/

Try Super High speed! LOL I can not play for more than 10 secs.

Hope you get higher scores than me. XD


### /******************** Demo ********************/

![Breakout Demo](demo.gif)
