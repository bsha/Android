Benjamin Sha
bensha@umich.edu
EECS 481 Homework 2 – readme.txt
https://github.com/bsha/Android

This is a replica of the game Connect4. 

The Layout:
1. The grid is where the game exists. 
2. Underneath the grid is a label that indicates which player’s turn it is. 
3. Right under the label is a “New Game” button that will clear the existing grid and start a new game. 
4. When the game wins, whether someone wins or it is a tie, a message will appear under the button indicating the outcome.

The Specifications:
1. Player 1 will always be the first player to go, even with you start a new game. 
2. The rules of the game are the same as regular Connect 4. You must take turns between player 1 and player 2. As soon as one of the players gets 4 in a row (vertical, horizontal, or diagonal), then a message appears underneath the “New Game” button, indicating the winner and that the game is over. If no one has 4 in a row and the grid is completely filled, then the message will indicate that the game is a tie. 
3. You can click anywhere that is part of the grid and the lowest open cell in that column will be occupied by the current player ‘s piece. If the column is already full, nothing will happen.

Checking Out and Building:
1. link to public repository: https://github.com/bsha/Android
2. The file is zipped, named as “BasicAppHW2_2.zip”. 
3. Unzip this file.
4. Import the project into eclipse
5. Run the program as Android application.
Note: This should work on any device/emulator with API level greater than 16 – works for API level 18. However, if the images do not show up properly due to resizing and the proportions, then run on Nexus One (3.7”, 480 x 800). This should show up fine.
