~~~
(instagram) E:\+라이브러리\Instagram-API-python>pip install InstagramApi
Looking in indexes: http://ftp.daumkakao.com/pypi/simple
Collecting InstagramApi
  Downloading http://mirror.kakao.com/pypi/packages/15/6d/f7eba7679fb40acb33ac75960c1aff269c2a75b32aff106266c85e3c0b93/InstagramAPI-1.0.2.tar.gz
Requirement already satisfied: requests==2.11.1 in e:\program\anaconda3\lib\site-packages (from InstagramApi) (2.11.1)
Requirement already satisfied: requests-toolbelt==0.7.0 in e:\program\anaconda3\lib\site-packages (from InstagramApi) (0.7.0)
Collecting moviepy==0.2.3.2 (from InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/e4/1f/fb4b8d9397f7952fcb594cb5df3061f00debae7ea92b3be9881c18b905ab/moviepy-0.2.3.2-py2.py3-none-any.whl (122kB)
    100% |████████████████████████████████| 133kB 936kB/s
Requirement already satisfied: numpy in c:\users\b3nn9\appdata\roaming\python\python36\site-packages (from moviepy==0.2.3.2->InstagramApi) (1.15.0)
Collecting tqdm==4.11.2 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/b7/0d/174388e99e21ee2c91ea318994c3f8744e26158e43cff0ec9d045bf08a96/tqdm-4.11.2-py2.py3-none-any.whl (46kB)
    100% |████████████████████████████████| 51kB ...
Collecting imageio==2.1.2 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/68/31/55cad23b6bd32afee6e4c7eec2f15266665879f8eaf812e3b843205d41ad/imageio-2.1.2.zip (3.3MB)
    100% |████████████████████████████████| 3.3MB 6.6MB/s
Collecting decorator==4.0.11 (from moviepy==0.2.3.2->InstagramApi)
  Downloading http://mirror.kakao.com/pypi/packages/00/cc/dd79ea98a0ff5a01d714c37eddd99cd0a71557113f1511921d1ef9a083b8/decorator-4.0.11-py2.py3-none-any.whl
Requirement already satisfied: pillow in e:\program\anaconda3\lib\site-packages (from imageio==2.1.2->moviepy==0.2.3.2->InstagramApi) (5.3.0)
Building wheels for collected packages: InstagramApi, imageio
  Running setup.py bdist_wheel for InstagramApi ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\3a\67\7c\4f66c582edcd6b2557c841594f8d66a89a3ad7e717cf942637
  Running setup.py bdist_wheel for imageio ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\29\8b\cf\2725ddca18b9dce1f88762ab51e3a4e51c4aa1c6b5377e81d2
Successfully built InstagramApi imageio
notebook 5.4.0 requires ipykernel, which is not installed.
jupyter 1.0.0 requires ipykernel, which is not installed.
ipywidgets 7.1.1 requires ipykernel>=4.5.1, which is not installed.
nes-py 0.11.0 has requirement tqdm>=4.19.5, but you'll have tqdm 4.11.2 which is incompatible.
gym-super-mario-bros 3.0.5 has requirement tqdm>=4.19.5, but you'll have tqdm 4.11.2 which is incompatible.
networkx 2.1 has requirement decorator>=4.1.0, but you'll have decorator 4.0.11 which is incompatible.
Installing collected packages: tqdm, imageio, decorator, moviepy, InstagramApi
  Found existing installation: tqdm 4.24.0
    Uninstalling tqdm-4.24.0:
      Successfully uninstalled tqdm-4.24.0
  Found existing installation: imageio 2.2.0
Cannot uninstall 'imageio'. It is a distutils installed project and thus we cannot accurately determine which files belong to it which would lead to only a partial uninstall.
You are using pip version 18.1, however version 19.0.3 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

(instagram) E:\+라이브러리\Instagram-API-python>python examples\test.py
~~~
