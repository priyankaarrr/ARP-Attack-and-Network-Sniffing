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

![image](https://github.com/user-attachments/assets/b492c8a9-5011-4c4e-881e-3c8fc5b9e5f7)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/e28c2171-5b8e-4aad-9bf7-5687191af13c)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![image](https://github.com/user-attachments/assets/823048b4-8ec6-4c60-89d6-f8fce19abb40)



In Kali issue the following commands:sudo dsnifff

## OUTPUT:

![image](https://github.com/user-attachments/assets/643bc26f-3d11-418b-8c02-012d1215f1a6)
## RESULT
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
