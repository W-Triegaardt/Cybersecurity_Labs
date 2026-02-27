# Lab 01 – Network Reconnaissance with Nmap

## Objective

To perform basic host discovery and port scanning within an isolated virtual lab environment.

## Lab Setup

| Machine | Role | IP Address |
|----------|--------|------------|
| Kali Linux | Attacker | 192.168.56.102 |
| Windows 11 VM | Workstation | 192.168.56.103 |
| Metasploitable 2 | Vulnerable Server | 192.168.56.101 |

Network Type: Host-Only Adapter (Isolated from Internet)

## Tools

- Nmap 7.95
- VirtualBox
- Kali Linux

## Scan 1 – Windows 11 VM

Command Used:

nmap 192.168.56.103

<img width="612" height="189" alt="image" src="https://github.com/user-attachments/assets/e37dd9c7-08d0-436c-8633-777de3c181cd" />

- Host is up.
- All 1000 default TCP ports were filtered.
- Indicates Windows Firewall is actively blocking inbound connections.

## Scan 2 – Metasploitable 2

Command Used:

nmap 192.168.56.101

<img width="612" height="551" alt="image" src="https://github.com/user-attachments/assets/0b279686-5d82-435c-8950-686ede6228a3" />


- Multiple open ports were identified.
