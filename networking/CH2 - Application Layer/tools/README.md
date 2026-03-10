# Network Tools

## Scanning
- Nmap
- Masscan

## Enumeration
- Netdiscover
- ARP-Scan

## Sniffing
- Wireshark
- tcpdump

## Exploitation
- Responder
- MITM6
_________________________________________________________________________

#                                      --------------- templete-------------------

# Nmap

## Purpose
Network discovery and port scanning.

## Common Commands

### Basic scan
nmap -sC -sV target

### Fast scan
nmap -T4 -F target

### Full port scan
nmap -p- target

## Use Cases
- Host discovery
- Service enumeration
- Port scanning

## Notes
Often first tool used during reconnaissance.
