# Mariolike-game-Super-santa-S
  Super santa S is a kind of simple mario-like game using X86 assembly language to program.<br>
  ![fordevoted](https://imgur.com/wSwHMLW.jpg "Super santa S")
## Overview
 Player can use keyboard to manipulate the character. the game is contain 3 level, and all of them are time limited, you can pass each level by getting over specific scores.assembly language is a kind of language between high-level language and machine language, and it is used to hardware device driver programming.<br> 
Compare Mario game, we remove the following characteritic:<br>
> Monster:    We remove the monster in orignal game, because player have no ability to attack, if there exist monsters, the game will be too difficult, besides that, we are more willing to see that player interact with maps.<br><br>
> Live:   We remove the characteristic of mutiple live, this change cooperate the setting of our storyline "Christmas", this special day is time limit, thus we think that "time" should gives more pressure than live.<br><br>
> Characteristic of box: we change money, mushroom to golden money(G), dangerous bonus(B), trap(T) and die(D).<br><br>

We add the folling feature into the game:<br>
> Maps:   Since we are willing to see player interact to maps. We add extra two maps into the game, that is three level.<br><br>
> Script:   We change the game feature form pass chanllenge to game script.<br><br>
> Limit of jump:    Mario can not jump if whe path he jump exist obstacle. player are encouraged to use `Tab` to change maps and conquer the obstacle. <br><br>

## Usages
   Dowload `make.bat` and excuate it to produce `mario.exe`, then excuate `mario.exe`.

## Feature
  * Opening animation: using `mwrite`and `delay` method to implement.
  * time counter: use `getMsecond` to fetch time to 12:00, then we can calculate passing time by call `getMsecond` many times.
  * interact with maps: we save maps in to one variables, and indentify if mario collision to maps.
  * mario move and gravity: we design a simple algorithms to implement gravity,and the animation of jump
  * position: record mario's position to accomplish the collision indentify.
## License
  ##### Fordevted
  NCU CSIE | 105802015 | 陳昱瑋  
## Contact
  210509fssh@gmail.com


