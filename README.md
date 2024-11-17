# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

### NAME:- Karna S
### REG NO: 212222110017
# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot (219)](https://github.com/user-attachments/assets/03c76e03-22a7-43eb-8ec6-b255f3f3abb7)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot (220)](https://github.com/user-attachments/assets/4379bb56-4e50-41f0-a109-cab19ae09361)

### DSNIFF:-

 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot (222)](https://github.com/user-attachments/assets/c88e0350-4914-49f8-ba86-5ba330625e36)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![374083629-39432531-60aa-4d43-8e30-eae0e4349de5](https://github.com/user-attachments/assets/532c199c-f22c-4700-a3c2-25be92facc2d)


Invoke the wireshark and examine the various menus  and controls of the tool:
![O5](https://github.com/user-attachments/assets/79da2025-11b2-4b43-946f-e6772cf22f0f)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
