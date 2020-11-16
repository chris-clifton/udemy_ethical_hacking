# Aggressive Website Technology Discovering on IP Range

## whatweb
- You can pass a range of IP addresses to scan
`whatweb 192.168.1.1-192.168.1.255 -v`

## Finding an IP Range
- For home network, run `sudo ifconfig`
- Next look at the netmask in order to figure out which octal groups are available to network devices
- Scan whatever range that is

## Changing aggression
most aggressive: `whatweb 192.168.1.1-192.168.1.255 --aggression 3 -v`
second-most aggressive: `whatweb 192.168.1.1-192.168.1.255 --aggression 2 -v`
legal on all websites: `whatweb 192.168.1.1-192.168.1.255 --aggression 1 -v`

## Options
`-v` provide verbose, more human readable output
`--no-errors` skips listing unused IPs
`--log-verbose=FILE` log verbose output to file 
