# nmap
- A network mapper
- Used to discover hosts and machines on a network by sending packets and analyzing responses

## Usage
`sudo nmap <hostname, IP address, networks> `
- Example arguments: scanme.nmap.org, microsoft.com/24, 192.168.0.1; 10.0.0-255.1-254
- Can take just a few seconds on local network, can take many hours on a big external network

## Scan a device
`sudo nmap 198.168.1.102`

## Scan a network
`sudo nmap 198.168.1/24` or `sudo nmap 198.168.1-255`
