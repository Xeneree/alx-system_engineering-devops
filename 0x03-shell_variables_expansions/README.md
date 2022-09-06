#!SHELL_INIT-FILES_VARIABLES_&_EXPANSIONS.

Task  0: Creates a script that creates an alias. $ alias ls="rm *" 

Task  1: Script prints "hello user"  $ echo hello $USER

Task  2:$ export PATH=$PATH:/action
The script adds "/action" to the "PATH'" . Which "./action" becomes the last directory when the shell looks for AA program

Task  3:Creates a script that counts the number of directories in the PATH. $  echo $PATH | tr -s ":" "\n" | wc -l

Task  4:$  "printenv" Makes a script that lists environment variables.

Task  5:The script lists all local variables and environment variables, and functions.
 $ "set"

Task  6: $ BEST="School"  The script creates a new local variable with name:BEST and value:School.

Task  7: $ export BEST='School' the script creates a new global variable with name:BEST and value:School.

Task  8: $ echo $((128+$TRUEKNOWLEDGE))  the command line  prints the result of the addition of 128 which the value is stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

Task  9:$  echo $(($POWER / $DIVIDE)) the script prints the result of "POWER" divided by "DIVIDE" followed by a new line.

Task 10:The command line $ "echo $(($BREATH**$LOVE))" displays the result of BREATH to the power LOVE, followed by a new line.

Task 11:$ echo "$((2#$BINARY))" 

Task 12:$ echo {a..z}{a..z} | tr ' ' "\n" | grep -v "oo" | sort.  The script prints all possible combinations of two letters, except oo. 

Task 13:When executed the script prints a number with two decimal places, followed by a new line. $ printf "%0.2f\n" $NUM

Task 14:$ printf "%x\n" $DECIMAL the script converts a number from base 10 to base 16

Task 15:The script encodes and decodes text using the rot13 encryption. Assume ASCII. $. tr 'a-zA-Z' 'n-za-mN-ZA-M'

Task 16:$ paste - - | cut -f1
the script prints every other line from the input, starting with the first line.

Task 17:the shell script adds the two numbers stored in the environment variables WATER and STIR and prints the result. $ printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 bestchol

