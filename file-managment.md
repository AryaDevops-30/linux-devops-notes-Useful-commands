#FILE VIEWING AND EDITING
cat file.txt
less file.txt
head file.txt
tail file.txt
nano file.txt
vi file.

#FILE PERMISSIONS
ls -l
chmod 755 script.sh
chmod +x script.sh
chown user:group file

#USER AND GROUP MANAGMENT
whoami
id
adduser username
passwd username
groupadd devops
usermod -aG devops username

#PACKAGE MANAGMENT (UBUNTU)
sudo apt update
sudo apt upgrade
sudo apt install nginx
sudo apt remove nginx

#PROCESS MANAGMENT
ps aux
top
htop
kill PID
kill -9 PID

