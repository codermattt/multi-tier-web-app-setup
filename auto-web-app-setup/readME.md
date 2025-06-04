# NOTES
- These were file I used for the auto-setup of the multi-stack web-application
Steps:
- In Git Bash or similar editor, cd to to folder with all the files including the Vagrant file
- "vagrant up"  (bring up the vms, will take a bit of time)
- once up, get static ip or hostname(webo1) of web01 that has maven tool, to compile and create package for source code,    so tomcat can run or host source code
- test web-app on browser by -> http://static ip/hostname
- if it works it will redirect traffic to tomcat for login prompt

