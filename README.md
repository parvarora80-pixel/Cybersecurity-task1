# Cybersecurity-task1

# Task 1 - Basic Network Scanning with Nmap

## Objective
Perform a basic network scan on localhost using Nmap.

## Tool Used
- Nmap 7.99
- Windows 11

## Command
nmap 127.0.0.1

## Result
The scan detected the localhost and identified multiple open TCP ports including:
- 135/tcp (msrpc)
- 445/tcp (microsoft-ds)
- 902/tcp
- 912/tcp
- 6646/tcp

## Conclusion
Nmap successfully scanned the local machine and identified open ports and running services.
## Service Version Scan

Command:
nmap -sV 127.0.0.1

This scan identified the versions of services running on the open ports.

## OS Detection

Command:
nmap -O 127.0.0.1

Operating System Detected:
Microsoft Windows 11

## Screenshots

### Basic Scan
![Basic Scan](Screenshot 2026-07-08 233834.png)

### Service Version Scan
![Service Scan](Screenshot 2026-07-09 000929.png)

### OS Detection Scan
![OS Scan](Screenshot 2026-07-09 001007.png)
