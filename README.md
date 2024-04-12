# NAME: SHIVARAM M.
# REG. NO.: 212223040195
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
![image](https://github.com/Shivaram2525/ARP-Attack-and-Network-Sniffing/assets/144226303/b7db1ed3-0a7b-4f9d-b73f-6cbef959360f)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Shivaram2525/ARP-Attack-and-Network-Sniffing/assets/144226303/22e133d1-b3db-4f4e-b558-74796a447e14)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Shivaram2525/ARP-Attack-and-Network-Sniffing/assets/144226303/3e7a086b-aa9d-40ed-a866-87d3f71e909b)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Shivaram2525/ARP-Attack-and-Network-Sniffing/assets/144226303/61064851-39c0-457a-a828-b64fc8602ba2)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Shivaram2525/ARP-Attack-and-Network-Sniffing/assets/144226303/9d82cb90-0a3e-4851-b5ae-40850a9bf9d7)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
