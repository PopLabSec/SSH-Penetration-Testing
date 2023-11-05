---
cover: ../.gitbook/assets/SSH Penetration Testing.png
coverY: 0
---

# SSH Service Info

When it comes to protecting your servers from unauthorized access, there are no longer any excuses. Every business should be aware and make sure their SSH service is secure.&#x20;

Secure Shell, or SSH, is an encrypted networking protocol commonly used to gain remote access to a server.&#x20;

It is an important protocol that is used to securely transfer data between two computers over an insecure network or the internet.

### Installation

### Connecting

```
ssh popdocs@192.168.1.10
```

### Config Files

```
nano /etc/ssh/sshd_config
```

#### Connect to Windows via Active Directory <a href="#connect-to-windows-via-active-directory" id="connect-to-windows-via-active-directory"></a>

```sh
ssh domain-name\\username@domain-controller
```

Securing Your SSH Service

