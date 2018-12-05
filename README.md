# Super Slime Soccer online two-player game
this project purpose is make some edit on Super Slime Soccer game source code and add two-player online feature to that.
in first step we have to decode source code of game.
## how to edit decode text
the decode text contains lists of sss.js variables and functions that names are coded. we read the code and add short description of their type and usage into decode!.txt file to findout how sss.js works.

### variables list
if you find out one variable is used for some reason or find the relation between variable and a part of game(like slime), you can add it's name into "variables" part.
the format of variables in this part is like this
```
variable_name -> the data type and usage or relation
#e.g.
#_I91 -> boolean related to songs format
```
if two variables are equal, point them like this
```
first_variable = second_variable -> ...
```
### functions list
in function decoding progress mabye you couldn't find the exact usage or clear description for what function is doing and just find out the function is about what or the main goal of that. don't worry and append your result to the "functions" list.  
to explain functions usage we use similar format
```
function_name -> usage or relation
#e.g.
#_E91 -> sets url of songs
```
### other parts of decode!.txt
the third part is sequence of function calling from browser and main function of code.



Good luck

