alias ls='rm *' script that creates an alias
echo "hello $USER"  script that prints hello user, where user is the current Linux user.
export PATH=$PATH:/action  script to Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))  script that counts the number of directories in the PATH.
printenv  script that lists environment variables.
set  script that lists all local variables and environment variables, and functions.
BEST="School"  script that creates a new local variable.
export BEST="School"  script that creates a new global variable.
echo $(($TRUEKNOWLEDGE + 128))  script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
echo $(($POWER / $DIVIDE))  script that prints the result of POWER divided by DIVIDE
echo $(($BREATH**$LOVE))  script that displays the result of BREATH to the power LOVE
echo $((2#$BINARY))  script that converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"  script that prints all possible combinations of two letters, except oo

