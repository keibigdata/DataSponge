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

## 아두이노 소프트웨어 설치하기
  
$ sudo apt-get install arduino
~~~
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following extra packages will be installed:
  arduino-core avr-libc avrdude binutils-avr extra-xdg-menus gcc-avr libftdi1 libjna-java
  libjna-jni librxtx-java
Suggested packages:
  arduino-mk avrdude-doc task-c-devel gcc-doc libjna-java-doc
The following NEW packages will be installed:
  arduino arduino-core avr-libc avrdude binutils-avr extra-xdg-menus gcc-avr libftdi1 libjna-java
  libjna-jni librxtx-java
0 upgraded, 11 newly installed, 0 to remove and 200 not upgraded.
Need to get 15.6 MB of archives.
After this operation, 108 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libftdi1 armhf 0.20-2 [16.7 kB]
Get:2 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main extra-xdg-menus all 1.0-4 [12.7 kB]
Get:3 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libjna-jni armhf 4.1.0-1 [40.5 kB]
Get:4 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libjna-java all 4.1.0-1 [163 kB]
Get:5 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main librxtx-java armhf 2.2pre2-13 [167 kB]
Get:6 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main binutils-avr armhf 2.24+Atmel3.4.4-1 [1,083 kB]
Get:7 http://archive.raspberrypi.org/debian/ jessie/main avrdude armhf 6.1-2+rpi1 [244 kB] 
Get:8 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main gcc-avr armhf 1:4.8.1+Atmel3.4.4-2 [7,513 kB]
Get:9 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main avr-libc all 1:1.8.0+Atmel3.4.4-1 [4,539 kB]
Get:10 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main arduino-core all 2:1.0.5+dfsg2-4 [655 kB]
Get:11 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main arduino all 2:1.0.5+dfsg2-4 [1,190 kB]
Fetched 15.6 MB in 5s (2,867 kB/s)
Selecting previously unselected package libftdi1:armhf.
(Reading database ... 113699 files and directories currently installed.)
Preparing to unpack .../libftdi1_0.20-2_armhf.deb ...
Unpacking libftdi1:armhf (0.20-2) ...
Selecting previously unselected package extra-xdg-menus.
Preparing to unpack .../extra-xdg-menus_1.0-4_all.deb ...
Unpacking extra-xdg-menus (1.0-4) ...
Selecting previously unselected package libjna-jni.
Preparing to unpack .../libjna-jni_4.1.0-1_armhf.deb ...
Unpacking libjna-jni (4.1.0-1) ...
Selecting previously unselected package libjna-java.
Preparing to unpack .../libjna-java_4.1.0-1_all.deb ...
Unpacking libjna-java (4.1.0-1) ...
Selecting previously unselected package librxtx-java.
Preparing to unpack .../librxtx-java_2.2pre2-13_armhf.deb ...
Unpacking librxtx-java (2.2pre2-13) ...
Selecting previously unselected package binutils-avr.
Preparing to unpack .../binutils-avr_2.24+Atmel3.4.4-1_armhf.deb ...
Unpacking binutils-avr (2.24+Atmel3.4.4-1) ...
Selecting previously unselected package gcc-avr.
Preparing to unpack .../gcc-avr_1%3a4.8.1+Atmel3.4.4-2_armhf.deb ...
Unpacking gcc-avr (1:4.8.1+Atmel3.4.4-2) ...
Selecting previously unselected package avrdude.
Preparing to unpack .../avrdude_6.1-2+rpi1_armhf.deb ...
Unpacking avrdude (6.1-2+rpi1) ...
Selecting previously unselected package avr-libc.
Preparing to unpack .../avr-libc_1%3a1.8.0+Atmel3.4.4-1_all.deb ...
Unpacking avr-libc (1:1.8.0+Atmel3.4.4-1) ...
Selecting previously unselected package arduino-core.
Preparing to unpack .../arduino-core_2%3a1.0.5+dfsg2-4_all.deb ...
Unpacking arduino-core (2:1.0.5+dfsg2-4) ...
Selecting previously unselected package arduino.
Preparing to unpack .../arduino_2%3a1.0.5+dfsg2-4_all.deb ...
Unpacking arduino (2:1.0.5+dfsg2-4) ...
Processing triggers for hicolor-icon-theme (0.13-1) ...
Processing triggers for man-db (2.7.0.2-5) ...
Processing triggers for gnome-menus (3.13.3-6) ...
Processing triggers for desktop-file-utils (0.22-1) ...
Processing triggers for mime-support (3.58) ...
Processing triggers for shared-mime-info (1.3-1) ...
Setting up libftdi1:armhf (0.20-2) ...
Setting up extra-xdg-menus (1.0-4) ...
Setting up libjna-jni (4.1.0-1) ...
Setting up libjna-java (4.1.0-1) ...
Setting up librxtx-java (2.2pre2-13) ...
Setting up binutils-avr (2.24+Atmel3.4.4-1) ...
Setting up gcc-avr (1:4.8.1+Atmel3.4.4-2) ...
Setting up avrdude (6.1-2+rpi1) ...
Setting up avr-libc (1:1.8.0+Atmel3.4.4-1) ...
Setting up arduino-core (2:1.0.5+dfsg2-4) ...
Setting up arduino (2:1.0.5+dfsg2-4) ...
Processing triggers for libc-bin (2.19-18+deb8u7) ...
~~~
$ sudo usermod -a -G tty pi  
$ sudo usermod -a -G dialout pi  
