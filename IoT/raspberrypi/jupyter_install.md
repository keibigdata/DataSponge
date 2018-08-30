### 주피터 노트북 설치
- 주피터 설치 : sudo pip3 install jupyter
~~~
pi@IoTBG:~$ sudo pip3 install jupyter
Collecting jupyter
  Downloading https://files.pythonhosted.org/packages/83/df/0f5dd132200728a86190397e1ea87cd76244e42d39ec5e88efd25b2abd7e/jupyter-1.0.0-py2.py3-none-any.whl
Collecting qtconsole (from jupyter)
  Downloading https://files.pythonhosted.org/packages/ff/1f/b340d52dee46fbbe8a097dce76d1197258bb599692159d94c80921fef9eb/qtconsole-4.4.1-py2.py3-none-any.whl (112kB)
    100% |████████████████████████████████| 112kB 715kB/s 
Collecting ipykernel (from jupyter)
  Downloading https://files.pythonhosted.org/packages/7a/de/a03a5c1f8b743675add3c98f1eb877c67bb29c5196ee6ce54e9c839d23cc/ipykernel-4.9.0-py3-none-any.whl (110kB)
    100% |████████████████████████████████| 112kB 1.1MB/s 
Collecting notebook (from jupyter)
  Downloading https://files.pythonhosted.org/packages/5e/7c/7fd8e9584779d65dfcad9fa2e09c76131a41f999f853a9c7026ed8585586/notebook-5.6.0-py2.py3-none-any.whl (8.9MB)
    100% |████████████████████████████████| 8.9MB 32kB/s 
Collecting jupyter-console (from jupyter)
  Downloading https://files.pythonhosted.org/packages/77/82/6469cd7fccf7958cbe5dce2e623f1e3c5e27f1bb1ad36d90519bc2d5d370/jupyter_console-5.2.0-py2.py3-none-any.whl
Collecting nbconvert (from jupyter)
  Downloading https://files.pythonhosted.org/packages/39/ea/280d6c0d92f8e3ca15fd798bbcc2ea141489f9539de7133d8fe10ea4b049/nbconvert-5.3.1-py2.py3-none-any.whl (387kB)
    100% |████████████████████████████████| 389kB 670kB/s 
Collecting ipywidgets (from jupyter)
  Downloading https://files.pythonhosted.org/packages/34/3a/5b258ea6d584f5a8527c2295d0ebf7ffb1654e3de38d37697f88bbef6621/ipywidgets-7.4.0-py2.py3-none-any.whl (109kB)
    100% |████████████████████████████████| 112kB 1.7MB/s 
Collecting jupyter-client>=4.1 (from qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/94/dd/fe6c4d683b09eb05342bd2816b7779663f71762b4fa9c2d5203d35d17354/jupyter_client-5.2.3-py2.py3-none-any.whl (89kB)
    100% |████████████████████████████████| 92kB 940kB/s 
Collecting pygments (from qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/02/ee/b6e02dc6529e82b75bb06823ff7d005b141037cb1416b10c6f00fc419dca/Pygments-2.2.0-py2.py3-none-any.whl (841kB)
    100% |████████████████████████████████| 849kB 328kB/s 
Collecting jupyter-core (from qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/1d/44/065d2d7bae7bebc06f1dd70d23c36da8c50c0f08b4236716743d706762a8/jupyter_core-4.4.0-py2.py3-none-any.whl (126kB)
    100% |████████████████████████████████| 133kB 1.7MB/s 
Collecting ipython-genutils (from qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/fa/bc/9bd3b5c2b4774d5f33b2d544f1460be9df7df2fe42f352135381c347c69a/ipython_genutils-0.2.0-py2.py3-none-any.whl
Collecting traitlets (from qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/93/d6/abcb22de61d78e2fc3959c964628a5771e47e7cc60d53e9342e21ed6cc9a/traitlets-4.3.2-py2.py3-none-any.whl (74kB)
    100% |████████████████████████████████| 81kB 1.9MB/s 
Collecting ipython>=4.0.0 (from ipykernel->jupyter)
  Downloading https://files.pythonhosted.org/packages/f7/62/2fef7db3a7b75e8099c3d9db2630ae5ba0b9eefefd91f7497862393d90e8/ipython-6.5.0-py3-none-any.whl (748kB)
    100% |████████████████████████████████| 757kB 368kB/s 
Collecting tornado>=4.0 (from ipykernel->jupyter)
  Downloading https://www.piwheels.org/simple/tornado/tornado-5.1-cp35-cp35m-linux_armv7l.whl (459kB)
    100% |████████████████████████████████| 460kB 101kB/s 
Collecting nbformat (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/da/27/9a654d2b6cc1eaa517d1c5a4405166c7f6d72f04f6e7eea41855fe808a46/nbformat-4.4.0-py2.py3-none-any.whl (155kB)
    100% |████████████████████████████████| 163kB 1.4MB/s 
Collecting terminado>=0.8.1 (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/2e/20/a26211a24425923d46e1213b376a6ee60dc30bcdf1b0c345e2c3769deb1c/terminado-0.8.1-py2.py3-none-any.whl
Collecting Send2Trash (from notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/49/46/c3dc27481d1cc57b9385aff41c474ceb7714f7935b1247194adae45db714/Send2Trash-1.5.0-py3-none-any.whl
Collecting pyzmq>=17 (from notebook->jupyter)
  Downloading https://www.piwheels.org/simple/pyzmq/pyzmq-17.1.2-cp35-cp35m-linux_armv7l.whl (4.7MB)
    100% |████████████████████████████████| 4.7MB 53kB/s 
Collecting prometheus-client (from notebook->jupyter)
  Downloading https://www.piwheels.org/simple/prometheus-client/prometheus_client-0.3.1-py3-none-any.whl
Requirement already satisfied: jinja2 in /usr/lib/python3/dist-packages (from notebook->jupyter)
Collecting prompt-toolkit<2.0.0,>=1.0.0 (from jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/04/d1/c6616dd03701e7e2073f06d5c3b41b012256e42b72561f16a7bd86dd7b43/prompt_toolkit-1.0.15-py3-none-any.whl (247kB)
    100% |████████████████████████████████| 256kB 986kB/s 
Collecting mistune>=0.7.4 (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/c8/8c/87f4d359438ba0321a2ae91936030110bfcc62fef752656321a72b8c1af9/mistune-0.8.3-py2.py3-none-any.whl
Collecting pandocfilters>=1.4.1 (from nbconvert->jupyter)
  Downloading https://www.piwheels.org/simple/pandocfilters/pandocfilters-1.4.2-py3-none-any.whl
Collecting bleach (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/94/aa/0f7ce53f8688bb9f80c0cffacc3964ddfe08321c509c0bfe5062848951f9/bleach-2.1.4-py2.py3-none-any.whl
Collecting entrypoints>=0.2.2 (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/cc/8b/4eefa9b47f1910b3d2081da67726b066e379b04ca897acfe9f92bac56147/entrypoints-0.2.3-py2.py3-none-any.whl
Collecting testpath (from nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/15/19/d7bc380c479a184e4a5a9ce516e4e2a773165f89b445f7cdced83d94de25/testpath-0.3.1-py2.py3-none-any.whl (161kB)
    100% |████████████████████████████████| 163kB 1.3MB/s 
Collecting widgetsnbextension~=3.4.0 (from ipywidgets->jupyter)
  Downloading https://files.pythonhosted.org/packages/83/03/ed063ec3ecf499d5491734822d8cadfc80f531a41ae1604277b25fbed795/widgetsnbextension-3.4.0-py2.py3-none-any.whl (2.2MB)
    100% |████████████████████████████████| 2.2MB 129kB/s 
Collecting python-dateutil>=2.1 (from jupyter-client>=4.1->qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/cf/f5/af2b09c957ace60dcfac112b669c45c8c97e32f94aa8b56da4c6d1682825/python_dateutil-2.7.3-py2.py3-none-any.whl (211kB)
    100% |████████████████████████████████| 215kB 696kB/s 
Collecting decorator (from traitlets->qtconsole->jupyter)
  Downloading https://files.pythonhosted.org/packages/bc/bb/a24838832ba35baf52f32ab1a49b906b5f82fb7c76b2f6a7e35e140bac30/decorator-4.3.0-py2.py3-none-any.whl
Requirement already satisfied: six in /usr/lib/python3/dist-packages (from traitlets->qtconsole->jupyter)
Collecting pexpect; sys_platform != "win32" (from ipython>=4.0.0->ipykernel->jupyter)
  Downloading https://files.pythonhosted.org/packages/89/e6/b5a1de8b0cc4e07ca1b305a4fcc3f9806025c1b651ea302646341222f88b/pexpect-4.6.0-py2.py3-none-any.whl (57kB)
    100% |████████████████████████████████| 61kB 1.8MB/s 
Requirement already satisfied: setuptools>=18.5 in /usr/lib/python3/dist-packages (from ipython>=4.0.0->ipykernel->jupyter)
Collecting simplegeneric>0.8 (from ipython>=4.0.0->ipykernel->jupyter)
  Downloading https://www.piwheels.org/simple/simplegeneric/simplegeneric-0.8.1-py3-none-any.whl
Collecting pickleshare (from ipython>=4.0.0->ipykernel->jupyter)
  Downloading https://files.pythonhosted.org/packages/9f/17/daa142fc9be6b76f26f24eeeb9a138940671490b91cb5587393f297c8317/pickleshare-0.7.4-py2.py3-none-any.whl
Collecting backcall (from ipython>=4.0.0->ipykernel->jupyter)
  Downloading https://www.piwheels.org/simple/backcall/backcall-0.1.0-py3-none-any.whl
Requirement already satisfied: jedi>=0.10 in /usr/lib/python3/dist-packages (from ipython>=4.0.0->ipykernel->jupyter)
Collecting jsonschema!=2.5.0,>=2.4 (from nbformat->notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/77/de/47e35a97b2b05c2fadbec67d44cfcdcd09b8086951b331d82de90d2912da/jsonschema-2.6.0-py2.py3-none-any.whl
Collecting ptyprocess; os_name != "nt" (from terminado>=0.8.1->notebook->jupyter)
  Downloading https://files.pythonhosted.org/packages/d1/29/605c2cc68a9992d18dada28206eeada56ea4bd07a239669da41674648b6f/ptyprocess-0.6.0-py2.py3-none-any.whl
Requirement already satisfied: MarkupSafe in /usr/lib/python3/dist-packages (from jinja2->notebook->jupyter)
Collecting wcwidth (from prompt-toolkit<2.0.0,>=1.0.0->jupyter-console->jupyter)
  Downloading https://files.pythonhosted.org/packages/7e/9f/526a6947247599b084ee5232e4f9190a38f398d7300d866af3ab571a5bfe/wcwidth-0.1.7-py2.py3-none-any.whl
Collecting html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre (from bleach->nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/a5/62/bbd2be0e7943ec8504b517e62bab011b4946e1258842bc159e5dfde15b96/html5lib-1.0.1-py2.py3-none-any.whl (117kB)
    100% |████████████████████████████████| 122kB 1.6MB/s 
Collecting webencodings (from html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre->bleach->nbconvert->jupyter)
  Downloading https://files.pythonhosted.org/packages/f4/24/2a3e3df732393fed8b3ebf2ec078f05546de641fe1b667ee316ec1dcf3b7/webencodings-0.5.1-py2.py3-none-any.whl
Installing collected packages: tornado, python-dateutil, decorator, ipython-genutils, traitlets, jupyter-core, pyzmq, jupyter-client, pygments, ptyprocess, pexpect, wcwidth, prompt-toolkit, simplegeneric, pickleshare, backcall, ipython, ipykernel, qtconsole, jsonschema, nbformat, terminado, Send2Trash, mistune, pandocfilters, webencodings, html5lib, bleach, entrypoints, testpath, nbconvert, prometheus-client, notebook, jupyter-console, widgetsnbextension, ipywidgets, jupyter
Successfully installed Send2Trash-1.5.0 backcall-0.1.0 bleach-2.1.4 decorator-4.3.0 entrypoints-0.2.3 html5lib-1.0.1 ipykernel-4.9.0 ipython-6.5.0 ipython-genutils-0.2.0 ipywidgets-7.4.0 jsonschema-2.6.0 jupyter-1.0.0 jupyter-client-5.2.3 jupyter-console-5.2.0 jupyter-core-4.4.0 mistune-0.8.3 nbconvert-5.3.1 nbformat-4.4.0 notebook-5.6.0 pandocfilters-1.4.2 pexpect-4.6.0 pickleshare-0.7.4 prometheus-client-0.3.1 prompt-toolkit-1.0.15 ptyprocess-0.6.0 pygments-2.2.0 python-dateutil-2.7.3 pyzmq-17.1.2 qtconsole-4.4.1 simplegeneric-0.8.1 terminado-0.8.1 testpath-0.3.1 tornado-5.1 traitlets-4.3.2 wcwidth-0.1.7 webencodings-0.5.1 widgetsnbextension-3.4.0
pi@IoTBG:~$
~~~
