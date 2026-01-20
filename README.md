# Network-scanning-Nmap
# Network Scanning & Enumeration using Nmap

## Objective
The aim of the project is to scan and enumerate the target computer network for open ports, running services, and OS information by employing Nmap.
This exercise can be very helpful in understanding the system’s attack surface and represents one of the most important steps in both offensive and defensive cyber operations.

## Tools Used
- Kali Linux (Attacker Machine)
- Metasploitable2 (Target Machine)
- Nmap
- VirtualBox

## Network Configuration
Both Kali Linux and Metasploitable2 were configured in 'Host-Only Adapter' mode to ensure they are on the same private network.

## Commands Used
nmap 192.168.56.101
nmap -sV 192.168.56.101
nmap -A 192.168.56.101
nmap -p- 192.168.56.101
