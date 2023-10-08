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
![image](https://github.com/Dhanashreemullaithasan/ARP-Attack-and-Network-Sniffing/assets/94165415/e1a1d7a9-501d-4392-91bb-31c14a0ca13e)
## OUTPUT:
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
![image](https://github.com/Dhanashreemullaithasan/ARP-Attack-and-Network-Sniffing/assets/94165415/3a6fbed5-3745-4b5d-af43-1aedaccfbf2f)
## OUTPUT:
 dsniff:
![image](https://github.com/Dhanashreemullaithasan/ARP-Attack-and-Network-Sniffing/assets/94165415/1f5a4533-4202-48e1-a1f6-5033b380cc41)

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
In Kali issue the following commands:sudo dsnifff
![image](https://github.com/Dhanashreemullaithasan/ARP-Attack-and-Network-Sniffing/assets/94165415/6fbd5b02-4b48-4349-8dcd-a2d4c16ab712)
## OUTPUT:
Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Dhanashreemullaithasan/ARP-Attack-and-Network-Sniffing/assets/94165415/e8f71f21-5c9c-46a3-a3b4-2b70ba9dbc3d)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
