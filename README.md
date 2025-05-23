# Common-Network-Tools

## Common Network Tools
### 1. Ping
Purpose: Checks if a device is reachable and how long it takes.

Command: ping [IP or domain]

#### Example: ping google.com

###2. Traceroute / Tracert
Purpose: Traces the path packets take to reach a destination.

#### Command:

Windows: tracert [domain]

Linux/macOS: traceroute [domain]

#### Example: tracert google.com

### 3. IPConfig / IFConfig
Purpose: Shows network configuration of your device.

#### Commands:

Windows: ipconfig

Linux/macOS: ifconfig or ip a

### 4. NSLookup
Purpose: Queries DNS to get domain-to-IP mappings.

Command: nslookup [domain]

#### Example: nslookup openai.com

### 5. Netstat
Purpose: Displays active network connections and listening ports.

#### Command: netstat -an

### 6. Nmap
Purpose: Network scanning, port discovery, security auditing.

#### Command: nmap [target IP or domain]

#### Example: nmap 192.168.1.1

### 7. Wireshark
Purpose: Packet capturing and deep network traffic analysis.

#### Type: GUI tool

Use: Inspect protocols, detect issues, analyze traffic flow.

### 8. Netcat (nc)
Purpose: Reads/writes data across network connections.

#### Command: nc [host] [port]

Use: Useful for testing ports, backdoors, and more.

### 9. Speedtest CLI
Purpose: Tests internet bandwidth and latency from the terminal.

#### Command: speedtest

### 10. ARP (Address Resolution Protocol)
Purpose: Shows and modifies the ARP table (IP ↔ MAC).

#### Command: arp -a

### 11. Host
Purpose: Simple DNS lookup tool (Linux/macOS).

#### Command: host [domain]

### Security & Penetration Tools (Advanced)<br>
Tool  -----------------------------  	Purpose<br>
Wireshark--------------------------	Deep traffic inspection<br>
Nmap	------------------------------Network scanning, port detection<br>
Aircrack-ng	-------------------------Wireless network cracking<br>
Tcpdump  -------------------------	CLI packet sniffer<br>
Metasploit------------------------	Penetration testing framework<br>

###  Web-based Network Tools
Tool	Use
https://ping.eu	Ping, traceroute, whois, DNS lookup
https://speedtest.net	Test internet speed
https://who.is	Domain & IP whois info

