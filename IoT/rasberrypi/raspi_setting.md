## 네트워크 구성하기  
  
$ vi /etc/network/interfaces  
~~~
......
#iface eth0 inet manual
auto eth0
iface eth0 inet static
address 192.168.100.245
network 192.168.100.0
netmask 255.255.255.0
gateway 192.168.100.254
#broadcast 192.168.1.2

dns-nameservers 192.168.1.2
......
~~~
  
## 리파지터리 변경하기  
  
$ sudo vi /etc/apt/sources.list  
~~~
#deb http://mirrordirector.raspbian.org/raspbian/ jessie main contrib non-free rpi
deb http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie main contrib non-free rpi

# Uncomment line below then 'apt-get update' to enable 'apt-get source'
#deb-src http://archive.raspbian.org/raspbian/ jessie main contrib non-free rpi
~~~
  
  
$ sudo apt-get update
~~~
Get:1 http://ftp.kaist.ac.kr jessie InRelease [14.9 kB]
Get:2 http://ftp.kaist.ac.kr jessie/main armhf Packages [9,537 kB]                     
Hit http://archive.raspberrypi.org jessie InRelease      
Get:3 http://ftp.kaist.ac.kr jessie/contrib armhf Packages [43.3 kB]                               
Get:4 http://ftp.kaist.ac.kr jessie/non-free armhf Packages [84.2 kB]                              
Get:5 http://ftp.kaist.ac.kr jessie/rpi armhf Packages [1,356 B]                                   
Ign http://ftp.kaist.ac.kr jessie/contrib Translation-en_GB                                    
Ign http://ftp.kaist.ac.kr jessie/contrib Translation-en                                       
Ign http://ftp.kaist.ac.kr jessie/main Translation-en_GB                        
Ign http://ftp.kaist.ac.kr jessie/main Translation-en                           
Ign http://ftp.kaist.ac.kr jessie/non-free Translation-en_GB                    
Ign http://ftp.kaist.ac.kr jessie/non-free Translation-en                       
Ign http://ftp.kaist.ac.kr jessie/rpi Translation-en_GB                         
Ign http://ftp.kaist.ac.kr jessie/rpi Translation-en                            
Hit http://archive.raspberrypi.org jessie/main armhf Packages                   
Hit http://archive.raspberrypi.org jessie/ui armhf Packages                                    
Ign http://archive.raspberrypi.org jessie/main Translation-en_GB                                   
Ign http://archive.raspberrypi.org jessie/main Translation-en                                      
Ign http://archive.raspberrypi.org jessie/ui Translation-en_GB                  
Ign http://archive.raspberrypi.org jessie/ui Translation-en
Fetched 9,681 kB in 23s (417 kB/s)            
Reading package lists... Done
~~~
