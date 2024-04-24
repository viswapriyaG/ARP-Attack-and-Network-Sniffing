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
![out1](https://github.com/viswapriyaG/ARP-Attack-and-Network-Sniffing/assets/131427787/32b8a9ab-e044-4e21-a6b7-7e9a738301d9)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![out2](https://github.com/viswapriyaG/ARP-Attack-and-Network-Sniffing/assets/131427787/9eba4cc2-d694-444e-bb28-823087debca4)


 dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![out3](https://github.com/viswapriyaG/ARP-Attack-and-Network-Sniffing/assets/131427787/22a3c6f5-8044-44f0-8f33-f6e4b729caca)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![out4](https://github.com/viswapriyaG/ARP-Attack-and-Network-Sniffing/assets/131427787/7562a011-aa01-4a53-83ff-b7b891224d6a)



Invoke the wireshark and examine the various menus  and controls of the tool:
![out5](https://github.com/viswapriyaG/ARP-Attack-and-Network-Sniffing/assets/131427787/1cd99fbb-8a0e-4c29-8208-b3013e28243d)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
