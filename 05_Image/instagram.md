## 인스타그램
- 환경만들기
~~~
(base) C:\Windows\system32>conda create -n instagram
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.5.11
  latest version: 4.6.7

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: E:\Program\Anaconda3\envs\instagram


Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate instagram
#
# To deactivate an active environment, use
#
#     $ conda deactivate


(base) C:\Windows\system32>conda activate instagram

(instagram) C:\Windows\system32>
~~~
- 필요한 라이브러리 설치
~~~
(instagram) E:\+라이브러리>git clone https://github.com/LevPasha/Instagram-API-python.git
Cloning into 'Instagram-API-python'...
remote: Enumerating objects: 541, done.
Rremote: Total 541 (delta 0), reused 0 (delta 0), pack-reused 541
Receiving objects:  98% (531/541), 148.01 KiB | 224.00 KiB/s
Receiving objects: 100% (541/541), 196.88 KiB | 299.00 KiB/s, done.
Resolving deltas: 100% (268/268), done.

(instagram) E:\+라이브러리>cd Instagram-API-python

(instagram) E:\+라이브러리\Instagram-API-python>pip install -r requirements.txt
Looking in indexes: http://ftp.daumkakao.com/pypi/simple
Collecting requests==2.11.1 (from -r requirements.txt (line 1))
  Downloading http://mirror.kakao.com/pypi/packages/ea/03/92d3278bf8287c5caa07dbd9ea139027d5a3592b0f4d14abf072f890fab2/r
equests-2.11.1-py2.py3-none-any.whl (514kB)
    100% |████████████████████████████████| 522kB 1.6MB/s
Collecting requests-toolbelt==0.7.0 (from -r requirements.txt (line 2))
  Downloading http://mirror.kakao.com/pypi/packages/57/60/cc85ca45c85585191e70e21687aeaa74ec4e555a1404628ba77b8af7d92e/r
equests_toolbelt-0.7.0-py2.py3-none-any.whl (52kB)
    100% |████████████████████████████████| 61kB ...
Collecting moviepy==0.2.2.11 (from -r requirements.txt (line 3))
  Downloading http://mirror.kakao.com/pypi/packages/ef/9d/6131378948f8a4a0f20a82b5212c3083bfcc06acfe0548976fcc2a98f34b/m
oviepy-0.2.2.11.tar.gz (107kB)
    100% |████████████████████████████████| 112kB 3.3MB/s
Requirement already satisfied: numpy in c:\users\b3nn9\appdata\roaming\python\python36\site-packages (from moviepy==0.2.
2.11->-r requirements.txt (line 3)) (1.15.0)
Requirement already satisfied: decorator in e:\program\anaconda3\lib\site-packages (from moviepy==0.2.2.11->-r requireme
nts.txt (line 3)) (4.2.1)
Requirement already satisfied: imageio in e:\program\anaconda3\lib\site-packages (from moviepy==0.2.2.11->-r requirement
s.txt (line 3)) (2.2.0)
Requirement already satisfied: tqdm in e:\program\anaconda3\lib\site-packages (from moviepy==0.2.2.11->-r requirements.t
xt (line 3)) (4.24.0)
Building wheels for collected packages: moviepy
  Running setup.py bdist_wheel for moviepy ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\2a\fd\a2\9d0ab33816ec3cd8977c969c60eb6b98f02aea8dad
6632dbec
Successfully built moviepy
Installing collected packages: requests, requests-toolbelt, moviepy
  Found existing installation: requests 2.18.4
    Uninstalling requests-2.18.4:
      Successfully uninstalled requests-2.18.4
Successfully installed moviepy-0.2.2.11 requests-2.11.1 requests-toolbelt-0.7.0
You are using pip version 18.1, however version 19.0.3 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

(instagram) E:\+라이브러리\Instagram-API-python>
~~~
