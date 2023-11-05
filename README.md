---
cover: .gitbook/assets/SSH_Penetration_Testing.png
coverY: 0
---

# Hacking Port 22

## Welcome aboard!

{% embed url="https://www.poplabsec.com/ssh-penetration-testing/" %}



<table data-card-size="large" data-view="cards"><thead><tr><th></th><th></th><th></th><th data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td>Enumeration</td><td></td><td></td><td></td><td><a href=".gitbook/assets/SSH_Penetration_Testing.png">SSH_Penetration_Testing.png</a></td></tr><tr><td>Exploitation</td><td></td><td></td><td></td><td></td></tr><tr><td>Post Exploitation</td><td></td><td></td><td></td><td></td></tr></tbody></table>



| Protocol       | Vulnerability Type        | Severity | Mitigation                                      |
| -------------- | ------------------------- | -------- | ----------------------------------------------- |
| 1. HTTP        | Injection Attacks         | High     | Web Application Firewalls                       |
| 2. SMTP        | Email Spoofing            | Medium   | SPF, DKIM, DMARC                                |
| 3. FTP         | Brute Force Attacks       | High     | Strong Passwords, Encryption                    |
| 4. Telnet      | Password Eavesdropping    | High     | SSH Replacement                                 |
| 5. SNMP        | Unauthorized Access       | Medium   | Community String Change                         |
| 6. DNS         | DNS Cache Poisoning       | High     | DNSSEC Implementation                           |
| 7. SMB/CIFS    | Ransomware Vulnerability  | Critical | Regular Patching, Segmentation                  |
| 8. RDP         | Remote Code Execution     | Critical | Network Segmentation, Strong Authentication     |
| 9. SSH         | Weak Passwords            | High     | Key-based Authentication, Disable Password Auth |
| 10. NTP        | Amplification DDoS Attack | High     | Rate Limiting, Monitoring                       |
| 11. POP3/IMAP  | Email Account Hijacking   | Medium   | Multi-Factor Authentication                     |
| 12. BGP        | Routing Attacks           | Critical | BGPSEC Implementation                           |
| 13. VoIP (SIP) | Eavesdropping             | Medium   | Secure VoIP Encryption                          |
| 14. IRC        | DDoS Attacks              | High     | Network Filtering, Monitoring                   |
| 15. SNMP Trap  | Information Leakage       | Low      | Access Control, Encryption                      |
