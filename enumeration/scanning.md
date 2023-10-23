---
cover: ../.gitbook/assets/SSH Penetration Testing.png
coverY: 0
---

# Scanning

### Check authentication methods

```
nmap -p22 <ip> --script ssh-auth-methods --script-args="ssh.user=root
```

### Send default nmap scripts for SSH

```
nmap -p22 <ip> -sC
```

### Retrieve version

```
nmap -p22 <ip> -sV
```

#### Retrieve SSH version using Metaploit

```
auxiliary/scanner/ssh/ssh_version
msf auxiliary(ssh_version) > set rhosts 192.168.1.17
msf auxiliary(ssh_version) > set rport 22
msf auxiliary(ssh_version) > exploit
```

### Retrieve supported algorithms

```
nmap -p22 <ip> --script ssh2-enum-algos
```

### Retrieve weak keys

```
nmap -p22 <ip> --script ssh-hostkey --script-args ssh_hostkey=full 
```
