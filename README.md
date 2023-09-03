# Nmap  
  
# Nmap informational flags  
--reason  
-v or -vv  
-d or -dd  
  
# Nmap scan types cheat sheet    
nmap -sN - TCP Null flag Scan (returns open/filtered ports)   
nmap -sF - TCP FIN flag Scan (returns open/filtered ports)   
nmap -sX - TCP Xmas FIN, PSH, and URG flags Scan (returns open/filtered ports)  
nmap -sA - TCP ACK flag Scan (returns ports which are not blocked by firewall)  
nmap -sW - TCP Window Scan (returns closed ports)  
nmap --scanflags {customFlags} - TCP Custom flags Scan  
nmap-S {spoofedIP} - Spoofed Scan  
nmap --spoof-mac {spoofedMac} - Spoofed MAC Scan  
nmap -D {decoyIP},ME - Decoy Scan	(can add any amount of decoyIP separated by a comma)   
nmap -sI {idleIP} - Idle/Zombie Scan  
  
# Nmap info about open ports  
sudo nmap -sV - Show services and versions  
sudo nmap --version-intensity {Level} - from 0 to 9  
sudo nmap -sV --version-light - Equal to 2  
sudo nmap -sV --version-all - Equal to 9  
sudo nmap -O - Show Operating system  
sudo nmap -sC - Run default script  
sudo nmap --script={selectedScript} - Run a script from the folder /nmap/scripts  
  
# Nmap save results  
sudo nmap {yourFlag} -oG {fileName} - Save in casual format  
sudo nmap {yourFlag} -oX {fileName} - Save in XML format  
sudo nmap {yourFlag} -oG {fileName} - Save in Grep format  
sudo nmap {yourFlag} -oA {fileName} - Save in all 3 formats  












