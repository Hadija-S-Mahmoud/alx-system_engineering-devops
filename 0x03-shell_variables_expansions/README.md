#0x03. Shell, init files, variables and expansions
##Learning Objectives
* alias ls='rm *' creates an alias with the name ls and value rm *
* echo "hello $USER" creates a script that prints hello user where user is the current Linux user.
* PATH=$PATH:/action Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
* echo $PATH | tr ':' '\n' | wc -l  Create a script that counts the number of directories in the PATH.
* Printenv
* Set
* BEST="School"
* export BEST="School"
* echo $((128+ $TRUEKNOWLEDGE))
* echo $(($POWER/$DIVIDE))
* echo $(($BREATH**$LOVE))
* echo $((2#$BINARY))
* echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"
* printf '%.2f\n' $NUM
* printf '%x\n' $DECIMAL
* tr 'A-Za-z' 'N-ZA-Mn-za-m'
* paste -d, - - | cut -d, -f1
* printf "%o\n" $((5#$(echo $WATER | tr 'water' '01234') + 5#$(echo $STIR | tr 'stir.' '01234'))) | tr '01234567' 'bestchol'
