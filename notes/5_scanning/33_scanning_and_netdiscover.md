# Scanning and Netdiscover

## Scanning
- Before we start scanning individual machines for open ports, first we need to find out what machines there even are on the network
- First part of scanning the network, is figuring out how many hosts you ahve active and what their IP addresses are

## arp tool
- arp is a packet and is used to discover hosts in a network
`arp -a`
- Sometimes you can't find all hosts because they need to be pinged first
  - For this reason, netdiscover is better

## netdiscover
`sudo netdiscover`
- Don't need to ping anything first, it just finds devices on the network
- Will actually run over all the different subnets/netmasks so you can control + C this one once you have the info you're after
