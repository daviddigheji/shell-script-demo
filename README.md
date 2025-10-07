# shell-script-demo
Some simple scrip to demonstrate the advantages of using shell script in linux environment
#!/bin/bash
# Short Introduction to bash scripting
# Author : David Digheji
OS=`cat /etc/centos-release`
UPTIME=`uptime`
USER=`whoami`
echo
echo This pc  is running a $OS .
echo It has been running for $UPTIME
echo
echo $USER is logged on to the computer.
