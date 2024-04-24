# Lexical-Analyzer
A lexer for a hypothetical C-- programming language

1. Download and save the lexer.l and Test.txt files to a location you will remember
2. Open Ubuntu or other application used to run a linux terminal
3. To install flex, run "sudo apt-get install flex" in the command prompt
4. Change directories to the folder holding the lexer.l and Test.txt files
5. Run the following commands 1 at a time to run the file and view the results:
   . "flex lexer.l"
   . "gcc lex.yy.c -o lexer -lfl"
   . "./lexer test.txt"
