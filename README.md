TCP-SYN-local-network-port-scanning
Cybersecurity Internship @ ElevateLabs | Performed local network port scanning using Nmap to identify open ports, analyze services, and assess basic network exposure.

Local Network Port Scanning

Objective

The goal of this task is to perform network reconnaissance on the local network using Nmap to identify open ports, understand service exposure, and assess potential vulnerabilities.

Execution

Determine Local IP Range
Used `ifconfig` (Linux) to identify the local IP and subnet.  
Example: `192.168.155.146/24`(mobile hotspot) and `172.16.22.58/21` (WiFI Broadband)
![command: iwconfig_output](https://github.com/user-attachments/assets/2f307eef-eaa0-483c-8747-f9529f4935b2)

![command:  ip addr_output](https://github.com/user-attachments/assets/abef9586-b914-4a78-8e81-b9224908186f)


Perform a TCP SYN Scan
bash - in Kali LINUX OS
nmap -sS 172.16.22.58/21
![command: nmap -sS_output](https://github.com/user-attachments/assets/b60d20cb-158a-4b6e-8126-7ec7df317e0d)



<----------------------------------------------------------------------------------------------------------->



Another task to capture Packet using WireShark
Packet captured from the local network - wlan0
![wireshark-packet-capturing](https://github.com/user-attachments/assets/44966f44-b58f-47d5-8539-5438824d77c5)

![wireshark-packet-details](https://github.com/user-attachments/assets/de2aa1ff-b554-4e2f-9b4f-8181d22054b7)


![wireshark-TCP-stream](https://github.com/user-attachments/assets/2f0db210-3610-4858-9a6a-5cec6642a9f0)

