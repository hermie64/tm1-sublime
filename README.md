# tm1-sublime
IBM Cognos TM1 syntax highlighting for Sublime Text

![screenshot](Other_Assets/intro.png "TM1 syntax highlighting in Sublime Text")

## Features
1.	The TM1 syntax highlighting is based on the Notepad++ version, but it has a dark theme to improve on readability.  
  a. Background is dark, but not completely black,  
  b. Comments are displayed in dark gray,  
  c. Strings are displayed in yellow,  
  d. Numbers are displayed in purple,  
  e. Operators like = , ; ( ) + etc. are displayed in dark red,  
  f. TM1 control statements like If, While etc. are displayed in green,  
  g. Majority of TM1 functions is displayed in light blue and bold,  
  h. TM1 functions without arguments are displayed in green and bold,  
  i. TM1 variables are displayed in yellow and bold,  
  j  Specific rules functions like FEEDERS, FEEDSTRINGS and SKIPCHECK are displayed in pink and bold,  
  k. Everything else is displayed in white.
  
2. The Notepad++ version hasn’t been updated for years. The Sublime Text version includes all functions from TM1 version 10.3.

3.	The Notepad++ syntax highlighter supports 3 "flavors" of functions (all uppercase (CELLPUTN) , all lowercase (cellputn), and case according to TM1 reference manual (CellPutN).  
The Sublime TM1 syntax highlighter highlights all functions regardless of their capitalization, but it highlights the functions that are __not__ capitalized according to reference manual in italics.
