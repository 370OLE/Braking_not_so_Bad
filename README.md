#BRAKING NOT SO BAD
***
Our Unity Project: Morna Müller, Jordan Peters, Ole Loechelt

Hello and welcome to this Game.

This Readme will provide information about:
    1. How to play the Game?
    2. Possible Errors
    3. How to test features and disable Game-Mechanics



##1. How to play the Game?
***

###1.1 Movement
```
Our game is based on the typical "Brick Braker". You start on the loading screan.
By pressing the "Play" button the first level loads. The Paddle down below can be moved to the right and the left.
The white little ball in the middle will start moving after two seconds have passed.
It will shoot towards the paddle in a random direction. The ball will bounce of the paddle and the walls exept the wall below.
To move the paddle you can either use the A/D button or the left and right arrow on the keyboard.
The angle of impact and the position where the ball impacts on the paddle contole the balls direction, so be carefull where the ball lands.
You can also safe the ball by hitting it with the side of the paddle, the ball will always shoot upwoards, but that will hit the paddle hard.
```

###1.2 Goal of the game
```
Each level has bricks that can only be destroyed when the ball hits them.
The bricks have different amounts of lives. Sometimes the lives are indicated by color, sometimes not.
Grey bricks can not be destroyed.
The Goal of the game is it to destroy all the destroable bricks and compleating all levels. 
You could also compiet against your friends by collecting more points than them. 
Hitting a destroyable brick gives 100 points.
The player has three lives. If the ball misses the paddle and flows below the paddle, the player loses one live.
the lives can be observed in the bottom left corner. The score in the top right and the level in the top left.
```



##2. Possible Errors
***
###2.1 Installation 
When you installl the game Unity might ask you if you want to install the game, because there are errors in it.
This can occure, clicing on the ignore button did not create more errors... :)

###2.2 Unity 
If you have one of these errors:
    - The referenced script (Unknown) on this Behaviour is missing!
    - The referenced script on this Behaviour (Game Object 'Game Manager') is missing!

The Game will run with no problems and you did nothing wrong.
There was a problem with a script I deleted and now the Error-Message seams unsolvable.

###2.3 Game
If the ball runns out of boundary, or ther is no text on the sides, you probably loaded the scene directly and not with the "Global" scene.
If you want to test out features of the level you need to do that. If you do not want to die all the time check out "3.2 What you can do:" down below.
The "Global" Scene is connected to the "GameManager" Script which controls most information in the game.
So you need to start with the "Start" Scene or the "Global" Scene.

###2.4 Other
If there are other Error-Messages, this should not be normal... hit me up.



##3. How to test features and disable Game-Mechanics
***
###3.1 How it should work:
You should be able to:
    - Start the game and play
    - Automaticly load the next level
    - Lose lives and gain no more than 4 
    - Hit Blocks and and collect points through the levels
    - Have fun :)

###3.2 What you can do:
Cheating is bad, so I do not recomend it. But to test out each level here is a trick.
Select the Level you want to cheat on and select the last "Wall" Object. If you disable 
the "Is Trigger" rectangle, you do not loose lives and will succed eventually.
If you want to check further levels, you can increase the Balls speed under the Ball Objekt -> Script.
I recommend a speed of 100 to test the current level and 500 to skipp the current level.+

### And now have Fun! :D
