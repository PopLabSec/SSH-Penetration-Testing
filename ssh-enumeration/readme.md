---
description: >-
  SSH enumeration is a key step in assessing the security of an SSH server. This
  tutorial covers the basics of SSH enumeration and provides a comprehensive
  look at SSH penetration testing techniques.
cover: ../.gitbook/assets/SSH Penetration Testing.png
coverY: 0
---

# Readme

SSH enumeration is an important skill for performing penetration tests on remote systems.&#x20;

This website provides step-by-step instructions on how to use various tools to enumerate SSH servers, detect potential flaws, and exploit those vulnerabilities for penetration testing.&#x20;

Gain the knowledge and skills you need to safely simulate real-world attack scenarios.

{% embed url="https://cli-ck.me/htb-pro-labs" %}

## Dangerous Settings

| Setting                    | Description                                 |
| -------------------------- | ------------------------------------------- |
| PasswordAuthentication yes | Allows password-based authentication.       |
| PermitEmptyPasswords yes   | Allows the use of empty passwords.          |
| PermitRootLogin yes        | Allows to log in as the root user.          |
| Protocol 1                 | Uses an outdated version of encryption.     |
| X11Forwarding yes          | Allows X11 forwarding for GUI applications. |
| AllowTcpForwarding yes     | Allows forwarding of TCP ports.             |
| PermitTunnel               | Allows tunneling.                           |
| DebianBanner yes           | Displays a specific banner when logging in. |
