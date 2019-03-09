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
- conda install ipykernel 후에 설치 
~~~
(instagram) E:\+라이브러리\Instagram-API-python>pip install InstagramApi
Looking in indexes: http://ftp.daumkakao.com/pypi/simple
Collecting InstagramApi
  Downloading http://mirror.kakao.com/pypi/packages/15/6d/f7eba7679fb40acb33ac75960c1aff269c2a75b32aff106266c85e3c0b93/I
nstagramAPI-1.0.2.tar.gz
Collecting requests==2.11.1 (from InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/ea/03/92d3278bf8287c5caa07dbd9ea139027d5a3592b0f4d14abf072f890fab2/r
equests-2.11.1-py2.py3-none-any.whl (514kB)
    100% |████████████████████████████████| 522kB 2.2MB/s
Collecting requests-toolbelt==0.7.0 (from InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/57/60/cc85ca45c85585191e70e21687aeaa74ec4e555a1404628ba77b8af7d92e/r
equests_toolbelt-0.7.0-py2.py3-none-any.whl (52kB)
    100% |████████████████████████████████| 61kB 3.9MB/s
Collecting moviepy==0.2.3.2 (from InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/e4/1f/fb4b8d9397f7952fcb594cb5df3061f00debae7ea92b3be9881c18b905ab/m
oviepy-0.2.3.2-py2.py3-none-any.whl (122kB)
    100% |████████████████████████████████| 133kB 2.2MB/s
Collecting decorator==4.0.11 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/00/cc/dd79ea98a0ff5a01d714c37eddd99cd0a71557113f1511921d1ef9a083b8/d
ecorator-4.0.11-py2.py3-none-any.whl
Collecting imageio==2.1.2 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/68/31/55cad23b6bd32afee6e4c7eec2f15266665879f8eaf812e3b843205d41ad/i
mageio-2.1.2.zip (3.3MB)
    100% |████████████████████████████████| 3.3MB 6.6MB/s
Collecting tqdm==4.11.2 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/b7/0d/174388e99e21ee2c91ea318994c3f8744e26158e43cff0ec9d045bf08a96/t
qdm-4.11.2-py2.py3-none-any.whl (46kB)
    100% |████████████████████████████████| 51kB ...
Collecting numpy (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/3a/3c/515afabfe4f29bfc0a67037efaf518c33d0076b32d22ba865241cee295c4/n
umpy-1.16.2-cp37-cp37m-win_amd64.whl (11.9MB)
    100% |████████████████████████████████| 11.9MB 6.6MB/s
Collecting pillow (from imageio==2.1.2->moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/20/59/edb6fe64a608afc9fd1faf3470774b4131b4be9d40c496b0c144033e249a/P
illow-5.4.1-cp37-cp37m-win_amd64.whl (2.0MB)
    100% |████████████████████████████████| 2.0MB ...
Building wheels for collected packages: InstagramApi, imageio
  Building wheel for InstagramApi (setup.py) ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\3a\67\7c\4f66c582edcd6b2557c841594f8d66a89a3ad7e717
cf942637
  Building wheel for imageio (setup.py) ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\29\8b\cf\2725ddca18b9dce1f88762ab51e3a4e51c4aa1c6b5
377e81d2
Successfully built InstagramApi imageio
Installing collected packages: requests, requests-toolbelt, decorator, numpy, pillow, imageio, tqdm, moviepy, InstagramA
pi
  Found existing installation: decorator 4.3.2
    Uninstalling decorator-4.3.2:
      Successfully uninstalled decorator-4.3.2
Successfully installed InstagramApi-1.0.2 decorator-4.0.11 imageio-2.1.2 moviepy-0.2.3.2 numpy-1.16.2 pillow-5.4.1 reque
sts-2.11.1 requests-toolbelt-0.7.0 tqdm-4.11.2

(instagram) E:\+라이브러리\Instagram-API-python>
~~~
