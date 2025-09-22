# Stephen-W-Elevate-Labs-Projects DAY-1
#Network Scanning using Nmap
**Cyber Security Internship - Task 1  
Network Port Scanning with Nmap**

Objective  
Learn to discover open ports on devices in my local network and understand network exposure.

### Tools Used  
- **Nmap** – For network scanning 
- **Linux Terminal** – For running commands  

### 📝 Steps I Followed  
 **Installed Nmap**  
   ```bash
   sudo apt update
   sudo apt install nmap -y
Found my local IP range

bash
Copy code
ifconfig
Found my IP: 192.168.1.xxx

Subnet: /24

My network range: 192.168.1.0/24

Performed TCP SYN Scan

bash
Copy code
nmap -sS 192.168.1.0/24
Saved Results to a File

bash
Copy code
nmap -sS 192.168.1.0/24 -oN scan_results.txt
