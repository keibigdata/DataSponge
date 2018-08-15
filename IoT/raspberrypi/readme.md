## 라즈베리파이 구성
  
- [라즈베리파이 3 B모델](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)  
- 마이크로SD카드(64GB)  
  
  
### 라즈비안 설치
- [라즈비안 다운로드](https://www.raspberrypi.org/downloads/raspbian/) : Raspbian Stretch with Desktop 4.14(2018-06-27)  
- [설치 전 마이크로SD카드에 넣기](https://www.raspberrypi.org/documentation/installation/installing-images/README.md) : [윈도우용 Win32DiskImager](https://www.raspberrypi.org/documentation/installation/installing-images/windows.md)  
- 마이크로SD카드 꼽고 부팅하면 바로 부팅됨  
- 네트워크 구성(무선랜 활성화 or [유선랜 활성화](./network_eth0.md))  
- 소프트웨어 저장소(Repository) 변경 : [다른 저장소 확인](https://www.raspbian.org/RaspbianMirrors/)  
KAIST가 대체로 사용량이 많아 부경대(Harukasan)로 선택  
- 한국 미러  
![한국 미러](./imgs/koreaMirrors.jpg)  
  
  
### [주피터 노트북 설치](./jupyter.md)
- PIP 리파지터리 변경(미러 변경) - [미러 보기](http://greenfishblog.tistory.com/255)  
(리눅스, 맥) $HOME/.pip/pip.conf / (윈도우) %appdata%\.pip\pip.ini  
~~~
[global]
index-url=http://ftp.daumkakao.com/pypi/simple
trusted-host=ftp.daumkakao.com
~~~
  
  
### [라즈베리파이 업데이트](./update.md)
-  
  
### [한글 사용](./hangul_20180806.md)  
- 
