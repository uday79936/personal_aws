step -1 : sudo useradd uday

step -2 : sudo passwd uday

step -3 : sudo visudo

step -4 : uday All  (for permissions)

step -5 : sudo vi /etc/ssh/sshd_config

step -6 : !wq   with saving

step -7 : :q!   without saving

step -8: sudo systemctl restart sshd

step -9:  username@ip address

step -10: sudo userdel -r uday

Bulid step by step process:step-1s

step-1:  To create EC2 instance

step-2: To download java11 version and update

step-3:  To install git and then clone the code

step-4:  To install maven

step-5:  mvn validate   to check weather project or not

step-6:  mvn test

step-7: wget to download the tomcat 9 version

step-8: To extract the file by using tar -xvzf or xvf and <path link>

step-9: cp -r kiran/target/* .war apache-tomcat-9.0.102/webapps/

step-10: cd  webapps

step-11: host-manager manager

step-12: cd bin and then startup.sh and shutdown.sh

step-13: conf and then change the username and password

step-14: finally we can deploy the project




