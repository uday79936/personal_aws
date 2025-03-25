step -1 : sudo useradd uday

step -2 : sudo passwd uday

step -3 : sudo visudo

step -4 : uday All  (for permissions)

step -5 : sudo vi /etc/ssh/sshd_config

step -6 : !wq

step -7 : :q!   without saving

step -8: sudo systemctl restart sshd

step -9:  username@ip address

step -10: sudo userdel -r uday
