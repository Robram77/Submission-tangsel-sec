## install package
- kali  : apt install nmap
- centOs: dfw install nmap
------------------------
## start ssh service
- kali  : systemctl start ssh
- centOs: systemctl start sshd
------------------------
## check service status ssh
-kali  : systemctl status ssh
- centOs: systemctl status sshd
------------------------
## add firewall rule
-kali  : ufw allow 22/tcp
-centOs: firewall-cmd --add-service=ssh --permanent
------------------------
## view system info
-kali  : uname -a
-centOs: hostnamectl
------------------------

