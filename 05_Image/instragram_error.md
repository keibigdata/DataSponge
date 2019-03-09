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
~~~
(instagram) E:\+라이브러리\Instagram-API-python>conda install ipykernel
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.5.11
  latest version: 4.6.7

Please update conda by running

    $ conda update -n base -c defaults conda



## Package Plan ##

  environment location: E:\Program\Anaconda3\envs\instagram

  added / updated specs:
    - ipykernel


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    zeromq-4.3.1               |       h33f27b4_3        52.4 MB
    decorator-4.3.2            |           py37_0          17 KB
    jedi-0.13.3                |           py37_0         234 KB
    sqlite-3.26.0              |       he774522_0         936 KB
    jupyter_client-5.2.4       |           py37_0         203 KB
    six-1.12.0                 |           py37_0          22 KB
    ca-certificates-2019.1.23  |                0         158 KB
    wheel-0.33.1               |           py37_0          57 KB
    pyzmq-18.0.0               |   py37ha925a31_0         466 KB
    certifi-2018.11.29         |           py37_0         146 KB
    setuptools-40.8.0          |           py37_0         663 KB
    colorama-0.4.1             |           py37_0          24 KB
    ipython-7.3.0              |   py37h39e3cac_0         1.1 MB
    openssl-1.1.1b             |       he774522_1         5.7 MB
    python-dateutil-2.8.0      |           py37_0         281 KB
    pip-19.0.3                 |           py37_0         1.8 MB
    prompt_toolkit-2.0.9       |           py37_0         487 KB
    python-3.7.2               |      h8c8aaf0_10        17.7 MB
    pygments-2.3.1             |           py37_0         1.3 MB
    parso-0.3.4                |           py37_0         121 KB
    ------------------------------------------------------------
                                           Total:        83.9 MB

The following NEW packages will be INSTALLED:

    backcall:         0.1.0-py37_0
    ca-certificates:  2019.1.23-0
    certifi:          2018.11.29-py37_0
    colorama:         0.4.1-py37_0
    decorator:        4.3.2-py37_0
    ipykernel:        5.1.0-py37h39e3cac_0
    ipython:          7.3.0-py37h39e3cac_0
    ipython_genutils: 0.2.0-py37_0
    jedi:             0.13.3-py37_0
    jupyter_client:   5.2.4-py37_0
    jupyter_core:     4.4.0-py37_0
    libsodium:        1.0.16-h9d3ae62_0
    openssl:          1.1.1b-he774522_1
    parso:            0.3.4-py37_0
    pickleshare:      0.7.5-py37_0
    pip:              19.0.3-py37_0
    prompt_toolkit:   2.0.9-py37_0
    pygments:         2.3.1-py37_0
    python:           3.7.2-h8c8aaf0_10
    python-dateutil:  2.8.0-py37_0
    pyzmq:            18.0.0-py37ha925a31_0
    setuptools:       40.8.0-py37_0
    six:              1.12.0-py37_0
    sqlite:           3.26.0-he774522_0
    tornado:          5.1.1-py37hfa6e2cd_0
    traitlets:        4.3.2-py37_0
    vc:               14.1-h0510ff6_4
    vs2015_runtime:   14.15.26706-h3a45250_0
    wcwidth:          0.1.7-py37_0
    wheel:            0.33.1-py37_0
    wincertstore:     0.2-py37_0
    zeromq:           4.3.1-h33f27b4_3

Proceed ([y]/n)?
~~~
