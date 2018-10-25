# TWFCS_Number_Guessing_Game

### Introduction ###

My name is Kyle Langley and this code I have uploaded was originally made as a mid-term project for my Computer Programming I class during my freshman spring semester at college. The basis of this code is a random number guessing game. For this game, the computer randomly picks a number of a set length and set size, and you must guess a number within those margins. The computer will tell you how many numbers you have correct and are in their correct positions and how many numbers you have correct but are misplaced but will not specify which number out of your numbers guessed it is talking about. You only have a set amount of guesses, so think carefully!

#### One Example of the Finished Program ####

### How to download? How to run? ###

This project was coded in the C++ IDE: #### DEV C++ ####
To download this IDE go to: https://sourceforge.net/projects/orwelldevcpp/files/latest/download
When you download the included project, first unzip the project. Once you have Dev C++ downloaded and open, run the Project1.dev file and it should open up all the included files needed to run the program. Once opened, press the compile and run button (F11) and it should load up on its own!

### Summary ####

This project is made up of three files: the main.cpp, the Project1.h, Project1.cpp.

The Project1.h consists of declarations of variables and functions. The Project1.cpp controls most of the system output of the program and controls much of the input as well. The input given is also ran through a length-checker to make sure that the input given fits the fixed code length.

The third, and chunky, file is the main.cpp which controls and executes the program. The beginning of this file contains most of the variables used to hold user inputs and guesses.  The game is created to run off of a while loop. This while loop can be found on line 44 of the main file and is set to run off of a game_over variable. As long as game_over is false, the program continues to run. This switch is set to true when either the user uses all of their guesses (designated by the MAX_GUESSES variable) or gets the number correct. The chunk of the while loop is made up of two for loops. These two for-loops cycle through the computer-generated number and the user-entered number and first checks to see what digits match perfectly and then check to see what numbers match but are misplaced in the user’s guess. If all numbers match, the game_over variable is switched to true and the user wins.
  
The rest of the code in main.cpp is used to print whether the user wins or loses (in how many guesses) and asks if the user would like to play again. Depending on the answer (Y/N), the program chooses to run again or stop. If the user chooses to stop, the program thanks the user and closes.

#### Extra Control ####

The three changable variables in this program that can be altered to increase or decrease difficulty are: number of max guesses, the codespan (how big the numbers can be), or the codelength (how long the generated code actually is)



These three variables can be changed at the start of the main file and once altered will change the program on its own. Just remember to re-compile and run to keep your changes.

