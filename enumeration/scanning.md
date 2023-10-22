---
cover: ../.gitbook/assets/SSH Penetration Testing.png
coverY: 0
---

# Scanning

```
nmap -sV -p22 192.168.1.10
```

```
nmap -p22 <ip> -sC # Send default nmap scripts for SSH
nmap -p22 <ip> -sV # Retrieve version
nmap -p22 <ip> --script ssh2-enum-algos # Retrieve supported algorythms 
nmap -p22 <ip> --script ssh-hostkey --script-args ssh_hostkey=full # Retrieve weak keys
nmap -p22 <ip> --script ssh-auth-methods --script-args="ssh.user=root" # Check authentication methods
```
