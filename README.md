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

Bulid step by step:

step-1: ec2 creation

step-2: install git and then git clone

step-3: install java 11 updated

step-4: install maven

step-5: mvn validate

step-6: mvn test

step-7: mvn tree

step-8: mvn clean (to clean their package)

step-9: mvn package

