# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
<br>

# AIM:


To explore network sniffing and ARP Attacks

<br>

## STEPS:

<br>

### Step 1:


Install kali linux either in partition or virtual box or in live mode

<br>

### Step 2:



Investigate on the various categories of tools as follows:

<br>

### Step 3:



Open terminal and try execute some kali linux commands

<br>

## ARP Attacks:  

<br>

ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a

<br>

## OUTPUT:

<br>


![image](https://github.com/user-attachments/assets/44010d6e-1e1b-4aac-8fa4-df6f50eedb67)



From parrot security issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

<br>

## OUTPUT:

![image](https://github.com/user-attachments/assets/54c5e341-cec9-47c0-b784-b9c2e66a2934)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/4990e795-4a95-41f5-a1f8-a4d872ab80c3)



In Parrot issue the following commands:
sudo dsniff
## OUTPUT:

![image](https://github.com/user-attachments/assets/e536adc8-e777-4638-a4ad-aed6bd249e4c)



Invoke the wireshark and examine the various menus  and controls of the tool:

![Screenshot 2024-10-07 143936](https://github.com/user-attachments/assets/159d328e-188d-480f-9c6c-a8593e8dfb7f)


## RESULT:
The parrot security tools for ARP Attack and Network Sniffing were identified successfully
