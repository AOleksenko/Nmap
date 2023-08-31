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

