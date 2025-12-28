# PROCESS MANAGMENT
ps aux                 # Show all running processes
top                    # Real-time process monitoring
htop                   # Advanced process viewer
# KILL PROCESS
kill PID
kill -9 PID
pkill process_name
#BACKGROUND AND FOREGROUND JOBS
command &
jobs
fg %1
bg %1
#PROCESS PRIORITY
nice -n 10 command
renice 5 -p PID
