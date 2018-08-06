### 주피터 노트북 설치
- 소프트웨어 저장소 정보 업데이트  
- 주피터 노트북 설치  
  
### 주피터 노트북 설정  
- 주피터 노트북 설정파일 생성
- 비밀번호 사전 설정을 위한 비밀번호 키 생성 : ipython
~~~
Python 3.5.3 (default, Jan 19 2017, 14:11:04) 
Type 'copyright', 'credits' or 'license' for more information
IPython 6.5.0 -- An enhanced Interactive Python. Type '?' for help.

In [1]: from notebook.auth import passwd

In [2]: passwd()
Enter password: 
Verify password: 
Out[2]: 'sha1:f74133ee4d9e:98825dd6100e180256e0f67124f384017b2e7f98'

In [3]: exit()
~~~
- 비밀번호 사전 설정 : vi .jupyter/jupyter_notebook_config.py
~~~
#c.NotebookApp.password = ''
~~~
~~~
c.NotebookApp.password = u'sha1:f74133ee4d9e:98825dd6100e180256e0f67124f384017b2e7f98'
~~~
- 세션 암호화를 위한 인증서 생성
~~~
pi@raspberrypi:~ $ cd .jupyter/
pi@raspberrypi:~/.jupyter $ openssl req -x509 -nodes -days 365 -newkey rsa:1024 -keyout jupyter.pem -out jupyter.pem   
Generating a 1024 bit RSA private key
..............................++++++
...........................++++++
writing new private key to 'jupyter.pem'
-----
You are about to be asked to enter information that will be incorporated
into your certificate request.
What you are about to enter is what is called a Distinguished Name or a DN.
There are quite a few fields but you can leave some blank
For some fields there will be a default value,
If you enter '.', the field will be left blank.
-----
Country Name (2 letter code) [AU]:KR
State or Province Name (full name) [Some-State]:Sejong
Locality Name (eg, city) []:
Organization Name (eg, company) [Internet Widgits Pty Ltd]:KEI
Organizational Unit Name (eg, section) []:BigData
Common Name (e.g. server FQDN or YOUR name) []:IoT_SR
Email Address []:dataq@kei.re.kr
~~~
- 인증서 적용
~~~
vi jupyter_notebook_config.py
......
#c.NotebookApp.certfile = ''
~~~
~~~
c.NotebookApp.certfile = '/home/pi/.jupyter/jupyter.pem'
~~~
- 주피터 노트북 실행 : jupyter notebook
