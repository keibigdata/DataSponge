## MongoDB 설치하기
  
$ sudo apt-get install mongodb  
~~~
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following extra packages will be installed:
  libboost-dev libboost1.55-dev libpcap0.8 libpcrecpp0 libsnappy1 mongodb-clients mongodb-dev
  mongodb-server
Suggested packages:
  libboost-doc libboost1.55-doc libboost-atomic1.55-dev libboost-chrono1.55-dev
  libboost-context1.55-dev libboost-coroutine1.55-dev libboost-date-time1.55-dev
  libboost-exception1.55-dev libboost-filesystem1.55-dev libboost-graph1.55-dev
  libboost-graph-parallel1.55-dev libboost-iostreams1.55-dev libboost-locale1.55-dev
  libboost-log1.55-dev libboost-math1.55-dev libboost-mpi1.55-dev libboost-mpi-python1.55-dev
  libboost-program-options1.55-dev libboost-python1.55-dev libboost-random1.55-dev
  libboost-regex1.55-dev libboost-serialization1.55-dev libboost-signals1.55-dev
  libboost-system1.55-dev libboost-test1.55-dev libboost-thread1.55-dev libboost-timer1.55-dev
  libboost-wave1.55-dev libboost1.55-tools-dev libmpfrc++-dev libntl-dev
The following NEW packages will be installed:
  libboost-dev libboost1.55-dev libpcap0.8 libpcrecpp0 libsnappy1 mongodb mongodb-clients
  mongodb-dev mongodb-server
0 upgraded, 9 newly installed, 0 to remove and 200 not upgraded.
Need to get 20.6 MB of archives.
After this operation, 208 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libpcap0.8 armhf 1.6.2-2 [121 kB]
Get:2 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libpcrecpp0 armhf 2:8.35-3.3+deb8u4 [140 kB]
Get:3 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libboost1.55-dev armhf 1.55.0+dfsg-3 [5,809 kB]
Get:4 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libboost-dev armhf 1.55.0.2 [3,378 B]
Get:5 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main mongodb-dev armhf 1:2.4.10-5+deb8u1 [1,073 kB]
Get:6 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main libsnappy1 armhf 1.1.2-3 [39.8 kB]
Get:7 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main mongodb-clients armhf 1:2.4.10-5+deb8u1 [10.1 MB]
Get:8 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main mongodb-server armhf 1:2.4.10-5+deb8u1 [3,245 kB]
Get:9 http://ftp.kaist.ac.kr/raspbian/raspbian/ jessie/main mongodb armhf 1:2.4.10-5+deb8u1 [12.2 kB]
Fetched 20.6 MB in 5s (4,055 kB/s)  
Selecting previously unselected package libpcap0.8:armhf.
(Reading database ... 117994 files and directories currently installed.)
Preparing to unpack .../libpcap0.8_1.6.2-2_armhf.deb ...
Unpacking libpcap0.8:armhf (1.6.2-2) ...
Selecting previously unselected package libpcrecpp0:armhf.
Preparing to unpack .../libpcrecpp0_2%3a8.35-3.3+deb8u4_armhf.deb ...
Unpacking libpcrecpp0:armhf (2:8.35-3.3+deb8u4) ...
Selecting previously unselected package libboost1.55-dev:armhf.
Preparing to unpack .../libboost1.55-dev_1.55.0+dfsg-3_armhf.deb ...
Unpacking libboost1.55-dev:armhf (1.55.0+dfsg-3) ...
Selecting previously unselected package libboost-dev:armhf.
Preparing to unpack .../libboost-dev_1.55.0.2_armhf.deb ...
Unpacking libboost-dev:armhf (1.55.0.2) ...
Selecting previously unselected package mongodb-dev.
Preparing to unpack .../mongodb-dev_1%3a2.4.10-5+deb8u1_armhf.deb ...
Unpacking mongodb-dev (1:2.4.10-5+deb8u1) ...
Selecting previously unselected package libsnappy1.
Preparing to unpack .../libsnappy1_1.1.2-3_armhf.deb ...
Unpacking libsnappy1 (1.1.2-3) ...
Selecting previously unselected package mongodb-clients.
Preparing to unpack .../mongodb-clients_1%3a2.4.10-5+deb8u1_armhf.deb ...
Unpacking mongodb-clients (1:2.4.10-5+deb8u1) ...
Selecting previously unselected package mongodb-server.
Preparing to unpack .../mongodb-server_1%3a2.4.10-5+deb8u1_armhf.deb ...
Unpacking mongodb-server (1:2.4.10-5+deb8u1) ...
Selecting previously unselected package mongodb.
Preparing to unpack .../mongodb_1%3a2.4.10-5+deb8u1_armhf.deb ...
Unpacking mongodb (1:2.4.10-5+deb8u1) ...
Processing triggers for man-db (2.7.0.2-5) ...
Processing triggers for systemd (215-17+deb8u6) ...
Setting up libpcap0.8:armhf (1.6.2-2) ...
Setting up libpcrecpp0:armhf (2:8.35-3.3+deb8u4) ...
Setting up libboost1.55-dev:armhf (1.55.0+dfsg-3) ...
Setting up libboost-dev:armhf (1.55.0.2) ...
Setting up mongodb-dev (1:2.4.10-5+deb8u1) ...
Setting up libsnappy1 (1.1.2-3) ...
Setting up mongodb-clients (1:2.4.10-5+deb8u1) ...
Setting up mongodb-server (1:2.4.10-5+deb8u1) ...
Adding system user `mongodb' (UID 113) ...
Adding new user `mongodb' (UID 113) with group `nogroup' ...
Not creating home directory `/home/mongodb'.
Adding group `mongodb' (GID 121) ...
Done.
Adding user `mongodb' to group `mongodb' ...
Adding user mongodb to group mongodb
Done.
Setting up mongodb (1:2.4.10-5+deb8u1) ...
Processing triggers for libc-bin (2.19-18+deb8u7) ...
Processing triggers for systemd (215-17+deb8u6) ...
~~~
$ sudo service mongodb start  
$ sudo service mongodb status  
~~~
[0m mongodb.service - An object/document-oriented database
   Loaded: loaded (/lib/systemd/system/mongodb.service; enabled)
   Active: active (running) since Tue 2018-06-05 13:39:04 UTC; 1min 37s ago
     Docs: man:mongod(1)
 Main PID: 20827 (mongod)
   CGroup: /system.slice/mongodb.service
           붴20827 /usr/bin/mongod --config /etc/mongodb.conf

Jun 05 13:39:04 iot02kei systemd[1]: Started An object/document-oriented database.
Jun 05 13:39:04 iot02kei mongod[20827]: all output going to: /var/log/mongodb/mongodb.log
Jun 05 13:40:37 iot02kei systemd[1]: Started An object/document-oriented database.
~~~
$ sudo service mongodb stop  
  
  
$ mongo  
~~~
MongoDB shell version: 2.4.10
connecting to: test
Tue Jun  5 14:40:16.308 Error: couldn't connect to server 127.0.0.1:27017 at src/mongo/shell/mongo.js:145
exception: connect failed
~~~
$ sudo service mongodb start  
$ mongo  
~~~
MongoDB shell version: 2.4.10
connecting to: test
Welcome to the MongoDB shell.
For interactive help, type "help".
For more comprehensive documentation, see
        http://docs.mongodb.org/
Questions? Try the support group
        http://groups.google.com/group/mongodb-user
Server has startup warnings: 
Tue Jun  5 14:40:24.528 [initandlisten] 
Tue Jun  5 14:40:24.528 [initandlisten] ** NOTE: This is a 32 bit MongoDB binary.
Tue Jun  5 14:40:24.528 [initandlisten] **       32 bit builds are limited to less than 2GB of data (or less with --journal).
Tue Jun  5 14:40:24.528 [initandlisten] **       See http://dochub.mongodb.org/core/32bit
Tue Jun  5 14:40:24.528 [initandlisten] 
> 
~~~
