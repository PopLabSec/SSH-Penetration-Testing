# Socks

```
ssh -D local_port user@host 
```

```
sed -i 's/^socks4.*/socks5 127.0.0.1 1080/' /etc/proxychains4.conf
```

```
proxychains4 -q nmap -sT -Pn 10.10.10.128
```
