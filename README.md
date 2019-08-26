# ansible-cisco-backup-telnet
Ansible script Cisco devices for backup config via telnet

Download this YAML and add inventory hostname in /etc/ansible/hosts file with some variable

# example
[vcisco] <br>
192.168.31.[83:85] <br><br>

[vcisco:vars]<br>
username=your-telnet-username <br>
password=your-telnet-password <br>
