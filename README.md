enable secret enpa55
line console 0
password conpa55
login
exit
ip domain-name ccnasecurity.com
username Admin secret Adminpa55
line vty 0 4
login local 
exit
crypto key generate rsa
1024

