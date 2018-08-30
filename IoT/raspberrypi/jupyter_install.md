~~~
pi@IoTBG:~/.pip$ pip install jupyter
Collecting jupyter
  Downloading http://mirror.kakao.com/pypi/packages/83/df/0f5dd132200728a86190397e1ea87cd76244e42d39ec5e88efd25b2abd7e/jupyter-1.0.0-py2.py3-none-any.whl
Collecting ipywidgets (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/34/3a/5b258ea6d584f5a8527c2295d0ebf7ffb1654e3de38d37697f88bbef6621/ipywidgets-7.4.0-py2.py3-none-any.whl (109kB)
    100% |████████████████████████████████| 112kB 1.4MB/s 
Collecting qtconsole (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/ff/1f/b340d52dee46fbbe8a097dce76d1197258bb599692159d94c80921fef9eb/qtconsole-4.4.1-py2.py3-none-any.whl (112kB)
    100% |████████████████████████████████| 112kB 817kB/s 
Collecting nbconvert (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/39/ea/280d6c0d92f8e3ca15fd798bbcc2ea141489f9539de7133d8fe10ea4b049/nbconvert-5.3.1-py2.py3-none-any.whl (387kB)
    100% |████████████████████████████████| 389kB 1.1MB/s 
Collecting notebook (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/5e/7c/7fd8e9584779d65dfcad9fa2e09c76131a41f999f853a9c7026ed8585586/notebook-5.6.0-py2.py3-none-any.whl (8.9MB)
    100% |████████████████████████████████| 8.9MB 1.4MB/s 
Collecting ipykernel (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/8e/65/c7ca3e3d05f9bd51b3010076b84f4e7304b12d0abf62a48f6cec2c90c019/ipykernel-4.8.2-py2-none-any.whl (108kB)
    100% |████████████████████████████████| 112kB 813kB/s 
Collecting jupyter-console (from jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/77/82/6469cd7fccf7958cbe5dce2e623f1e3c5e27f1bb1ad36d90519bc2d5d370/jupyter_console-5.2.0-py2.py3-none-any.whl
Collecting nbformat>=4.2.0 (from ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/da/27/9a654d2b6cc1eaa517d1c5a4405166c7f6d72f04f6e7eea41855fe808a46/nbformat-4.4.0-py2.py3-none-any.whl (155kB)
    100% |████████████████████████████████| 163kB 872kB/s 
Collecting widgetsnbextension~=3.4.0 (from ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/83/03/ed063ec3ecf499d5491734822d8cadfc80f531a41ae1604277b25fbed795/widgetsnbextension-3.4.0-py2.py3-none-any.whl (2.2MB)
    100% |████████████████████████████████| 2.2MB 976kB/s 
Collecting ipython<6.0.0,>=4.0.0; python_version < "3.3" (from ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/b0/88/d996ab8be22cea1eaa18baee3678a11265e18cf09974728d683c51102148/ipython-5.8.0-py2-none-any.whl (760kB)
    100% |████████████████████████████████| 768kB 1.0MB/s 
Collecting traitlets>=4.3.1 (from ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/93/d6/abcb22de61d78e2fc3959c964628a5771e47e7cc60d53e9342e21ed6cc9a/traitlets-4.3.2-py2.py3-none-any.whl (74kB)
    100% |████████████████████████████████| 81kB 935kB/s 
Collecting jupyter-core (from qtconsole->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/1d/44/065d2d7bae7bebc06f1dd70d23c36da8c50c0f08b4236716743d706762a8/jupyter_core-4.4.0-py2.py3-none-any.whl (126kB)
    100% |████████████████████████████████| 133kB 924kB/s 
Collecting jupyter-client>=4.1 (from qtconsole->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/94/dd/fe6c4d683b09eb05342bd2816b7779663f71762b4fa9c2d5203d35d17354/jupyter_client-5.2.3-py2.py3-none-any.whl (89kB)
    100% |████████████████████████████████| 92kB 903kB/s 
Collecting ipython-genutils (from qtconsole->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/fa/bc/9bd3b5c2b4774d5f33b2d544f1460be9df7df2fe42f352135381c347c69a/ipython_genutils-0.2.0-py2.py3-none-any.whl
Collecting pygments (from qtconsole->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/02/ee/b6e02dc6529e82b75bb06823ff7d005b141037cb1416b10c6f00fc419dca/Pygments-2.2.0-py2.py3-none-any.whl (841kB)
    100% |████████████████████████████████| 849kB 835kB/s 
Collecting entrypoints>=0.2.2 (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/cc/8b/4eefa9b47f1910b3d2081da67726b066e379b04ca897acfe9f92bac56147/entrypoints-0.2.3-py2.py3-none-any.whl
Collecting pandocfilters>=1.4.1 (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/4c/ea/236e2584af67bb6df960832731a6e5325fd4441de001767da328c33368ce/pandocfilters-1.4.2.tar.gz
Collecting testpath (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/15/19/d7bc380c479a184e4a5a9ce516e4e2a773165f89b445f7cdced83d94de25/testpath-0.3.1-py2.py3-none-any.whl (161kB)
    100% |████████████████████████████████| 163kB 1.9MB/s 
Collecting bleach (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/94/aa/0f7ce53f8688bb9f80c0cffacc3964ddfe08321c509c0bfe5062848951f9/bleach-2.1.4-py2.py3-none-any.whl
Collecting jinja2 (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/7f/ff/ae64bacdfc95f27a016a7bed8e8686763ba4d277a78ca76f32659220a731/Jinja2-2.10-py2.py3-none-any.whl (126kB)
    100% |████████████████████████████████| 133kB 929kB/s 
Collecting mistune>=0.7.4 (from nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/c8/8c/87f4d359438ba0321a2ae91936030110bfcc62fef752656321a72b8c1af9/mistune-0.8.3-py2.py3-none-any.whl
Collecting tornado>=4 (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/45/ec/f2a03a0509bcfca336bef23a3dab0d07504893af34fd13064059ba4a0503/tornado-5.1.tar.gz (516kB)
    100% |████████████████████████████████| 522kB 1.2MB/s 
Collecting Send2Trash (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/13/2e/ea40de0304bb1dc4eb309de90aeec39871b9b7c4bd30f1a3cdcb3496f5c0/Send2Trash-1.5.0.tar.gz
Collecting pyzmq>=17 (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/b9/6a/bc9277b78f5c3236e36b8c16f4d2701a7fd4fa2eb697159d3e0a3a991573/pyzmq-17.1.2.tar.gz (1.1MB)
    100% |████████████████████████████████| 1.1MB 1.2MB/s 
Collecting prometheus-client (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/a1/b1/08de091b392fec31da9bd3f5edd9214ec1c6931dd81641610ac20f3ff934/prometheus_client-0.3.1.tar.gz
Collecting terminado>=0.8.1 (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/2e/20/a26211a24425923d46e1213b376a6ee60dc30bcdf1b0c345e2c3769deb1c/terminado-0.8.1-py2.py3-none-any.whl
Collecting ipaddress; python_version == "2.7" (from notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/fc/d0/7fc3a811e011d4b388be48a0e381db8d990042df54aa4ef4599a31d39853/ipaddress-1.0.22-py2.py3-none-any.whl
Collecting prompt-toolkit<2.0.0,>=1.0.0 (from jupyter-console->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/d1/b0/1a6c262da35c779dd79550137aa7c298a424987240a28792ec5ccf48f848/prompt_toolkit-1.0.15-py2-none-any.whl (247kB)
    100% |████████████████████████████████| 256kB 858kB/s 
Collecting jsonschema!=2.5.0,>=2.4 (from nbformat>=4.2.0->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/77/de/47e35a97b2b05c2fadbec67d44cfcdcd09b8086951b331d82de90d2912da/jsonschema-2.6.0-py2.py3-none-any.whl
Collecting setuptools>=18.5 (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/66/e8/570bb5ca88a8bcd2a1db9c6246bb66615750663ffaaeada95b04ffe74e12/setuptools-40.2.0-py2.py3-none-any.whl (568kB)
    100% |████████████████████████████████| 573kB 935kB/s 
Collecting backports.shutil-get-terminal-size; python_version == "2.7" (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/7d/cd/1750d6c35fe86d35f8562091737907f234b78fdffab42b29c72b1dd861f4/backports.shutil_get_terminal_size-1.0.0-py2.py3-none-any.whl
Collecting pickleshare (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/9f/17/daa142fc9be6b76f26f24eeeb9a138940671490b91cb5587393f297c8317/pickleshare-0.7.4-py2.py3-none-any.whl
Collecting pexpect; sys_platform != "win32" (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/89/e6/b5a1de8b0cc4e07ca1b305a4fcc3f9806025c1b651ea302646341222f88b/pexpect-4.6.0-py2.py3-none-any.whl (57kB)
    100% |████████████████████████████████| 61kB 1.3MB/s 
Collecting pathlib2; python_version == "2.7" or python_version == "3.3" (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/66/a7/9f8d84f31728d78beade9b1271ccbfb290c41c1e4dc13dbd4997ad594dcd/pathlib2-2.3.2-py2.py3-none-any.whl
Collecting decorator (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/bc/bb/a24838832ba35baf52f32ab1a49b906b5f82fb7c76b2f6a7e35e140bac30/decorator-4.3.0-py2.py3-none-any.whl
Collecting simplegeneric>0.8 (from ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/3d/57/4d9c9e3ae9a255cd4e1106bb57e24056d3d0709fc01b2e3e345898e49d5b/simplegeneric-0.8.1.zip
Collecting enum34; python_version == "2.7" (from traitlets>=4.3.1->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/c5/db/e56e6b4bbac7c4a06de1c50de6fe1ef3810018ae11732a50f15f62c7d050/enum34-1.1.6-py2-none-any.whl
Collecting six (from traitlets>=4.3.1->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/67/4b/141a581104b1f6397bfa78ac9d43d8ad29a7ca43ea90a2d863fe3056e86a/six-1.11.0-py2.py3-none-any.whl
Collecting python-dateutil>=2.1 (from jupyter-client>=4.1->qtconsole->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/cf/f5/af2b09c957ace60dcfac112b669c45c8c97e32f94aa8b56da4c6d1682825/python_dateutil-2.7.3-py2.py3-none-any.whl (211kB)
    100% |████████████████████████████████| 215kB 1.0MB/s 
Collecting configparser>=3.5; python_version == "2.7" (from entrypoints>=0.2.2->nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/7c/69/c2ce7e91c89dc073eb1aa74c0621c3eefbffe8216b3f9af9d3885265c01c/configparser-3.5.0.tar.gz
Collecting html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre (from bleach->nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/a5/62/bbd2be0e7943ec8504b517e62bab011b4946e1258842bc159e5dfde15b96/html5lib-1.0.1-py2.py3-none-any.whl (117kB)
    100% |████████████████████████████████| 122kB 885kB/s 
Collecting MarkupSafe>=0.23 (from jinja2->nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/4d/de/32d741db316d8fdb7680822dd37001ef7a448255de9699ab4bfcbdf4172b/MarkupSafe-1.0.tar.gz
Collecting backports_abc>=0.4 (from tornado>=4->notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/7d/56/6f3ac1b816d0cd8994e83d0c4e55bc64567532f7dc543378bd87f81cebc7/backports_abc-0.5-py2.py3-none-any.whl
Collecting futures (from tornado>=4->notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/2d/99/b2c4e9d5a30f6471e410a146232b4118e697fa3ffc06d6a65efde84debd0/futures-3.2.0-py2-none-any.whl
Collecting singledispatch (from tornado>=4->notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/c5/10/369f50bcd4621b263927b0a1519987a04383d4a98fb10438042ad410cf88/singledispatch-3.4.0.3-py2.py3-none-any.whl
Collecting ptyprocess; os_name != "nt" (from terminado>=0.8.1->notebook->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/d1/29/605c2cc68a9992d18dada28206eeada56ea4bd07a239669da41674648b6f/ptyprocess-0.6.0-py2.py3-none-any.whl
Collecting wcwidth (from prompt-toolkit<2.0.0,>=1.0.0->jupyter-console->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/7e/9f/526a6947247599b084ee5232e4f9190a38f398d7300d866af3ab571a5bfe/wcwidth-0.1.7-py2.py3-none-any.whl
Collecting functools32; python_version == "2.7" (from jsonschema!=2.5.0,>=2.4->nbformat>=4.2.0->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/5e/1a/0aa2c8195a204a9f51284018562dea77e25511f02fe924fac202fc012172/functools32-3.2.3-2.zip
Collecting scandir; python_version < "3.5" (from pathlib2; python_version == "2.7" or python_version == "3.3"->ipython<6.0.0,>=4.0.0; python_version < "3.3"->ipywidgets->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/16/2a/557af1181e6b4e30254d5a6163b18f5053791ca66e251e77ab08887e8fe3/scandir-1.9.0.tar.gz
Collecting webencodings (from html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre->bleach->nbconvert->jupyter)
  Downloading http://mirror.kakao.com/pypi/packages/f4/24/2a3e3df732393fed8b3ebf2ec078f05546de641fe1b667ee316ec1dcf3b7/webencodings-0.5.1-py2.py3-none-any.whl
Building wheels for collected packages: pandocfilters, tornado, Send2Trash, pyzmq, prometheus-client, simplegeneric, configparser, MarkupSafe, functools32, scandir
  Running setup.py bdist_wheel for pandocfilters ... done
  Stored in directory: /home/pi/.cache/pip/wheels/02/0b/9d/e2566f11a148399d760a9efd0cd298451c12f55e12bcfa685e
  Running setup.py bdist_wheel for tornado ... done
  Stored in directory: /home/pi/.cache/pip/wheels/2c/8e/9c/c8d9897756b014d6236c977cf0dc3e07c3904638657b2d1dfe
  Running setup.py bdist_wheel for Send2Trash ... done
  Stored in directory: /home/pi/.cache/pip/wheels/46/1d/79/e35210f67eb36706002688e8744d5b3c38727603c1f9d35409
  Running setup.py bdist_wheel for pyzmq ... done
  Stored in directory: /home/pi/.cache/pip/wheels/16/b6/2b/da597671ca3bcb6b85d4c94a17e34776c88f0dcee110793ea4
  Running setup.py bdist_wheel for prometheus-client ... done
  Stored in directory: /home/pi/.cache/pip/wheels/58/1e/fd/8e131ce8880e5234f344cd9dfa85a94d544c502ad2595b2ff9
  Running setup.py bdist_wheel for simplegeneric ... done
  Stored in directory: /home/pi/.cache/pip/wheels/e5/7a/f2/be118ef84c085ec9bed4c332ba248320d5f0a890c7524ad676
  Running setup.py bdist_wheel for configparser ... done
  Stored in directory: /home/pi/.cache/pip/wheels/19/e2/d3/5cac2336d25971c995fba2d51c5f36a49786b5da491933ed87
  Running setup.py bdist_wheel for MarkupSafe ... done
  Stored in directory: /home/pi/.cache/pip/wheels/a6/32/38/eb4c07532344666eb417405e65ac72551a48c7a20257ecc9a2
  Running setup.py bdist_wheel for functools32 ... done
  Stored in directory: /home/pi/.cache/pip/wheels/bd/11/8e/9cf4b3b94300627353176529325f6705138c95198c981e8d61
  Running setup.py bdist_wheel for scandir ... done
  Stored in directory: /home/pi/.cache/pip/wheels/ae/b5/07/2eb18a6e126e8c9577dcda1740c7d0bcf121d59715852d7a57
Successfully built pandocfilters tornado Send2Trash pyzmq prometheus-client simplegeneric configparser MarkupSafe functools32 scandir
Installing collected packages: enum34, six, decorator, ipython-genutils, traitlets, jupyter-core, functools32, jsonschema, nbformat, python-dateutil, pyzmq, backports-abc, futures, singledispatch, tornado, jupyter-client, Send2Trash, configparser, entrypoints, pandocfilters, testpath, webencodings, html5lib, bleach, MarkupSafe, jinja2, pygments, mistune, nbconvert, prometheus-client, ptyprocess, terminado, ipaddress, setuptools, wcwidth, prompt-toolkit, backports.shutil-get-terminal-size, scandir, pathlib2, pickleshare, pexpect, simplegeneric, ipython, ipykernel, notebook, widgetsnbextension, ipywidgets, qtconsole, jupyter-console, jupyter
Successfully installed MarkupSafe-1.0 Send2Trash-1.5.0 backports-abc-0.5 backports.shutil-get-terminal-size-1.0.0 bleach-2.1.4 configparser-3.5.0 decorator-4.3.0 entrypoints-0.2.3 enum34-1.1.6 functools32-3.2.3.post2 futures-3.2.0 html5lib-1.0.1 ipaddress-1.0.22 ipykernel-4.8.2 ipython-5.8.0 ipython-genutils-0.2.0 ipywidgets-7.4.0 jinja2-2.10 jsonschema-2.6.0 jupyter-1.0.0 jupyter-client-5.2.3 jupyter-console-5.2.0 jupyter-core-4.4.0 mistune-0.8.3 nbconvert-5.3.1 nbformat-4.4.0 notebook-5.6.0 pandocfilters-1.4.2 pathlib2-2.3.2 pexpect-4.6.0 pickleshare-0.7.4 prometheus-client-0.3.1 prompt-toolkit-1.0.15 ptyprocess-0.6.0 pygments-2.2.0 python-dateutil-2.7.3 pyzmq-17.1.2 qtconsole-4.4.1 scandir-1.9.0 setuptools-40.2.0 simplegeneric-0.8.1 singledispatch-3.4.0.3 six-1.11.0 terminado-0.8.1 testpath-0.3.1 tornado-5.1 traitlets-4.3.2 wcwidth-0.1.7 webencodings-0.5.1 widgetsnbextension-3.4.0
pi@IoTBG:~/.pip$ 
~~~
