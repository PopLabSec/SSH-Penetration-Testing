# VPN

```
ip tuntap add mode tun tun0
ip link set dev tun0 up
ip addr add 10.1.1.10/24 dev tun0
```

```
ip route add 10.10.10.0/24 via 10.1.1.10
```

```
PermitTunnel yes
```

```
ip tuntap add mode tun tun0
ip link set dev tun0 up
ip addr add 10.1.1.20/24 dev tun0
```

```
ip route add 10.1.1.0/24 via 10.1.1.20
```

```
sysctl -w net.ipv4.conf.tun0.forwarding=1
sysctl -w net.ipv4.conf.ens36.forwarding=1
```

```
iptables -t nat -A POSTROUTING -o <interface> -j MASQUERADE
```
