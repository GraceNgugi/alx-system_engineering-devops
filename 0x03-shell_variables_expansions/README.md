alias ls= "rm *" - Create a script that creates an alias.Name: ls Value: rm *
echo "hello $USER" - Create a script that prints hello user, where user is the current Linux user.
export PATH="$PATH:/action" - Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $PATH | tr ':' '\n' | grep -c / - Create a script that counts the number of directories in the PATH.
printenv - Create a script that lists environment variables.
set - Create a script that lists all local variables and environment variables, and functions.
export BEST="School"  - Create a script that creates a new global variable.
echo $((128 + TRUEKNOWLEDGE))- Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $((POWER / DIVIDE))- Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
echo $((POWER ** LOVE)) - Write a script that displays the result of BREATH to the power LOVE
echo $((2#$BINARY)) - Write a script that converts a number from base 2 to base 10.
printf "%x\n" $DECIMAL - Write a script that converts a number from base 10 to base 16. The number in base 10 is stored in the environment variableDECIMAL.
tr A-Za-z N-ZA-Mn-za-m - Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
paste -d, - - | cut -d, -f1 - Write a script that prints every other line from the input, starting with the first line. 


