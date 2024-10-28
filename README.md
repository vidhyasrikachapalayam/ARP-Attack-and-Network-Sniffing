# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode
### Step 2:
Investigate on the various categories of tools as follows:
### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/402b99d5-77c8-472f-878f-9ef99d3a6cde)

From kali linux issue the command : sudo arpspoof -i eth0 -t

## OUTPUT:
![image](https://github.com/user-attachments/assets/9a56d40e-66fc-4e01-aa24-6213bc1377f9)

dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/user-attachments/assets/0e2215d4-a894-4437-afd3-f6cdec475863)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/79b7a4c9-110b-43be-8743-cbc675781345)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/b17cfd02-8d17-4527-aa11-b2278a30cd82)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
