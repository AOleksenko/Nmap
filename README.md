# Nmap
Nmap cheat sheet
sudo nmap -sN - TCP Null flag Scan (returns open/filtered ports)
sudo nmap -sF - TCP FIN flag Scan (returns open/filtered ports)
sudo nmap -sX - TCP Xmas FIN, PSH, and URG flags Scan (returns open/filtered ports)
sudo nmap -sA - TCP ACK flag Scan (returns ports which are not blocked by firewall)
sudo nmap -sW - TCP Window Scan (returns closed ports)
sudo nmap --scanflags yourCustomFlags - TCP Custom flags Scan	
