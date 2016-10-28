# Bingo-Game

<h2>If you are part of this project, please 'Star' this Project!</h2>
---
<ul>
  <li><strong>Project Name</strong> : Bingo-Game</li>
  <li><strong>Project description</strong> : Allow user to create a bingo board using any values, size, or scoring features they desire. The program will randomize the values for mass printing where each board is (presumably) unique, or for a single board that can be played as a desktop app.</li>
  
  <li><strong>Project Example</strong> : User will be able to input words inside of application <strong>OR</strong> Read words from a file. Once they input the words into the program, they will be able to chose the board size (Needs to be a square n x n). Then, users are able to chose which word to pick inside of each items on board. Once they finish and hit *START* button. Program will generate random words and start the game Bingo.</li>
  
  <li><strong>Used Languages</strong> : C#</li>
  
  <li><strong>Used Editors</strong> : Visual Studio 2015, VS Code</li>
  
  <li><strong>Start Date</strong> : October 28, 2016</li>
</ul>


---------- Konnor's Note ----------<br>
Input:  Manual (ask user one-by-one until they indicate they are finished), .txt, .csv, Database

Dimensions: Rectangle or Square
  -Enter columns and rows manually
  -Suggest dimensions by rounding down to the nearest square/rectangle (keeping the shape nearly square -- if you are given 39 values, you don't want to suggest 3 X 13 nor round down to 2 X 19). Each board will then have less values than the total pool (so if a word/term is called, not everyone playing will be placing a tile down).
  -Suggest by rounding up, keeping similar features as in the round-down explanation. Note that on both, the values are suggested and can still be edited (perhaps have an option that if you increase one [rows/columns], the other repopulates). Each board will have duplicate values from the total pool/set, but not necessarily the same ones as each other.
  -An option to have the center square be a free space if there are an odd number of spaces.

Display            -Header Bar or no (to Display a title; eg. "Bio Bingo!")
(Results/Board):   -Fonts, font-size, italics, bold, color, etc.
                   -Themes available (suggested color/font combos, like in MS Office)
                   -Starting suggestion a plain theme that's easy on the printer

There is both an output for a/many distinct static, printable board/s, as well as the computer game.

Electronic Game:  Using vocabulary words, the user/creator also provides definitions through one of the input means. A player must provide a proper definition through Multiple Choice to be able to place a tile on the called square.
