The following command will indicate which ports are listening for TCP connections from the network. 
# sudo nmap -sT -O localhost
The following command will indicate which ports are listening for UDP connections from the network.
# sudo nmap -sU -O localhost
The following command will indicate every TCP and UDP open port -
# sudo nmap -n -PN -sT -sU -p- localhost
