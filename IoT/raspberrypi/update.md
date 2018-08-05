### 라즈베리파이 업데이트(라즈비안 업데이트)
- 소프트웨어 저장소 정보 업데이트 : sudo apt-get update  
~~~
Get:1 http://ftp.harukasan.org/raspbian/raspbian stretch InRelease [15.0 kB]
Hit:2 http://archive.raspberrypi.org/debian stretch InRelease                                                         
Get:3 http://ftp.harukasan.org/raspbian/raspbian stretch/main armhf Packages [11.7 MB]                      
Get:4 http://raspbian.raspberrypi.org/raspbian stretch InRelease [15.0 kB]                                  
Get:5 http://raspbian.raspberrypi.org/raspbian stretch/main armhf Packages [11.7 MB]
Fetched 23.3 MB in 22s (1,019 kB/s)                                                                                   
Reading package lists... Done
~~~
- 라즈비안 정보 확인 : uname -a  
~~~
Linux raspberrypi 4.14.50-v7+ #1122 SMP Tue Jun 19 12:26:26 BST 2018 armv7l GNU/Linux
~~~
- 라즈비안 업데이트 : sudo rpi-update  
~~~
 *** Raspberry Pi firmware updater by Hexxeh, enhanced by AndrewS and Dom
 *** Performing self-update
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 13545  100 13545    0     0  17431      0 --:--:-- --:--:-- --:--:-- 17454
 *** Relaunching after update
 *** Raspberry Pi firmware updater by Hexxeh, enhanced by AndrewS and Dom
 *** We're running for the first time
 *** Backing up files (this will take a few minutes)
 *** Backing up firmware
 *** Backing up modules 4.14.50-v7+
#############################################################
This update bumps to rpi-4.14.y linux tree
Be aware there could be compatibility issues with some drivers
Discussion here:
https://www.raspberrypi.org/forums/viewtopic.php?f=29&t=197689
##############################################################
 *** Downloading specific firmware revision (this will take a few minutes)
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   168    0   168    0     0    181      0 --:--:-- --:--:-- --:--:--   181
100 56.0M  100 56.0M    0     0   562k      0  0:01:42  0:01:42 --:--:--  548k
 *** Updating firmware
 *** Updating kernel modules
 *** depmod 4.14.59-v7+
 *** depmod 4.14.59+
 *** Updating VideoCore libraries
 *** Using HardFP libraries
 *** Updating SDK
 *** Running ldconfig
 *** Storing current firmware revision
 *** Deleting downloaded files
 *** Syncing changes to disk
 *** If no errors appeared, your firmware was successfully updated to efba34cc68065768250cff56873e325fc2fe180c
 *** A reboot is needed to activate the new firmware
~~~
- 라즈비안 재시작 : sudo reboot  
(재시작 후)  
- 라즈비안 정보 확인 : uname -a  
~~~
Linux raspberrypi 4.14.59-v7+ #1131 SMP Thu Aug 2 15:57:42 BST 2018 armv7l GNU/Linux
~~~
- 소프트웨어 저장소 정보 및 소프트웨어 업데이트 : sudo apt-get update && sudo apt-get upgrade  
- 라즈비안 재시작 : sudo reboot  
