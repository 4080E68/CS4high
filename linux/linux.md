# ifconfig
```
root@kali:~# ifconfig
docker0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        (1)inet 172.17.0.1  (3)netmask 255.255.0.0  broadcast 172.17.255.255
        ether 02:42:26:5d:91:3b  txqueuelen 0  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  (2)mtu 1500
        inet 10.0.2.15  netmask 255.255.255.0  broadcast 10.0.2.255
        inet6 fe80::a00:27ff:fee2:ff9  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:e2:0f:f9  txqueuelen 1000  (Ethernet)
        RX packets 12418  bytes 17665773 (16.8 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 5325  bytes 328516 (320.8 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 22  bytes 1194 (1.1 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 22  bytes 1194 (1.1 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
root@kali:~# ^C
```
