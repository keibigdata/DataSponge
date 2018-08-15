$ sudo vi /etc/network/interfaces
~~~
auto eth0
iface eth0 inet static
address 192.168.100.245
network 192.168.100.0
netmask 255.255.255.0
gateway 192.168.100.254
broadcast 192.168.1.2
~~~
