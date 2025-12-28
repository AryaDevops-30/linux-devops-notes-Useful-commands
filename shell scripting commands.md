*BASIC SHELL STRUCTURE
#!/bin/bash -Shebang – tells the system to use Bash shell.
#chmod +x script.sh -Makes the script executable.
#./script.sh  -Runs the script.

*VARIABLES
#name="Arya"
echo $name
read user
echo "Hello $user"

*CONDITIONS AND STATEMENT
If–Else
if [ $a -gt $b ]
then
  echo "a is greater"
else
  echo "b is greater"
fi
if [ -f file.txt ]
then
  echo "File exists"
fi

*LOOPS

For Loop
for i in 1 2 3 4 5
do
  echo $i
done

While Loop
while [ $count -le 5 ]
do
  echo $count
  ((count++))
done

*FUNCTIONS
myfunc() {
  echo "Hello from function"
}

myfunc

*FILES AND DIRECTORIES
[ -f file.txt ]   # File exists
[ -d folder ]     # Directory exists
[ -x script.sh ]  # Executable

*INPUT AND ARGUMENTS
echo $1   # First argument
echo $2   # Second argument
echo $#   # Number of arguments
echo $@   # All arguments

* DATE AND TIME
date
date +"%d-%m-%Y"

*EXIT STATUS
echo $?

*COMMAND SUBSTITUTION
today=$(date)
echo "Today is $today"

*DEBUGGING SCRIPT
bash -x script.sh







