### 윈도우에서 코엔엘(KoNLPy) 설치  
- 파이썬 인스톨러(PIP) 업데이트
~~~
(base) C:\Windows\system32>pip install --upgrade pip
Requirement already up-to-date: pip in e:\program\anaconda3\lib\site-packages (18.0)
~~~
- JPype1 설치하기(아래와 같이 오류가 난다면 -> 요기)
~~~
(base) C:\Windows\system32>pip install JPype1
Collecting JPype1
  Using cached https://files.pythonhosted.org/packages/c4/4b/60a3e63d51714d4d7ef1b1efdf84315d118a0a80a5b085bb52a7e2428cdc/JPype1-0.6.3.tar.gz
Building wheels for collected packages: JPype1
  Running setup.py bdist_wheel for JPype1 ... error
  Complete output from command e:\program\anaconda3\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\b3nn9\\AppData\\Local\\Temp\\pip-install-7sqtu459\\JPype1\\setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f.r
ead().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" bdist_wheel -d C:\Users\b3nn9\AppData\Local\Temp\pip-wheel-u4o57w_7 --python-tag cp36:
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-3.6
  creating build\lib.win-amd64-3.6\jpype
  copying jpype\imports.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\JClassUtil.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\nio.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\reflect.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_classpath.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_core.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_cygwin.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_darwin.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_gui.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jarray.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jboxed.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jclass.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jcollection.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jexception.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jio.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jobject.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jpackage.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jproxy.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jvmfinder.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_jwrapper.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_linux.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_properties.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_pykeywords.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_refdaemon.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\_windows.py -> build\lib.win-amd64-3.6\jpype
  copying jpype\__init__.py -> build\lib.win-amd64-3.6\jpype
  creating build\lib.win-amd64-3.6\jpype\awt
  copying jpype\awt\__init__.py -> build\lib.win-amd64-3.6\jpype\awt
  creating build\lib.win-amd64-3.6\jpype\awt\event
  copying jpype\awt\event\WindowAdapter.py -> build\lib.win-amd64-3.6\jpype\awt\event
  copying jpype\awt\event\__init__.py -> build\lib.win-amd64-3.6\jpype\awt\event
  creating build\lib.win-amd64-3.6\jpypex
  copying jpypex\__init__.py -> build\lib.win-amd64-3.6\jpypex
  creating build\lib.win-amd64-3.6\jpypex\swing
  copying jpypex\swing\AbstractAction.py -> build\lib.win-amd64-3.6\jpypex\swing
  copying jpypex\swing\pyutils.py -> build\lib.win-amd64-3.6\jpypex\swing
  copying jpypex\swing\__init__.py -> build\lib.win-amd64-3.6\jpypex\swing
  running build_ext
  C:\Users\b3nn9\AppData\Local\Temp\pip-install-7sqtu459\JPype1\setup.py:173: FeatureNotice: Turned ON Numpy support for fast Java array access
    FeatureNotice)
  building '_jpype' extension
  error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": http://landinghub.visualstudio.com/visual-cpp-build-tools

  ----------------------------------------
  Failed building wheel for JPype1
  Running setup.py clean for JPype1
Failed to build JPype1
Installing collected packages: JPype1
  Running setup.py install for JPype1 ... error
    Complete output from command e:\program\anaconda3\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\b3nn9\\AppData\\Local\\Temp\\pip-install-7sqtu459\\JPype1\\setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f
.read().replace('\r\n', '\n');f.close();exec(compile(code, __file__, 'exec'))" install --record C:\Users\b3nn9\AppData\Local\Temp\pip-record-6cr5tk5k\install-record.txt --single-version-externally-managed --compile:
    running install
    running build
    running build_py
    creating build
    creating build\lib.win-amd64-3.6
    creating build\lib.win-amd64-3.6\jpype
    copying jpype\imports.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\JClassUtil.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\nio.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\reflect.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_classpath.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_core.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_cygwin.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_darwin.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_gui.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jarray.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jboxed.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jclass.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jcollection.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jexception.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jio.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jobject.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jpackage.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jproxy.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jvmfinder.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_jwrapper.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_linux.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_properties.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_pykeywords.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_refdaemon.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\_windows.py -> build\lib.win-amd64-3.6\jpype
    copying jpype\__init__.py -> build\lib.win-amd64-3.6\jpype
    creating build\lib.win-amd64-3.6\jpype\awt
    copying jpype\awt\__init__.py -> build\lib.win-amd64-3.6\jpype\awt
    creating build\lib.win-amd64-3.6\jpype\awt\event
    copying jpype\awt\event\WindowAdapter.py -> build\lib.win-amd64-3.6\jpype\awt\event
    copying jpype\awt\event\__init__.py -> build\lib.win-amd64-3.6\jpype\awt\event
    creating build\lib.win-amd64-3.6\jpypex
    copying jpypex\__init__.py -> build\lib.win-amd64-3.6\jpypex
    creating build\lib.win-amd64-3.6\jpypex\swing
    copying jpypex\swing\AbstractAction.py -> build\lib.win-amd64-3.6\jpypex\swing
    copying jpypex\swing\pyutils.py -> build\lib.win-amd64-3.6\jpypex\swing
    copying jpypex\swing\__init__.py -> build\lib.win-amd64-3.6\jpypex\swing
    running build_ext
    C:\Users\b3nn9\AppData\Local\Temp\pip-install-7sqtu459\JPype1\setup.py:173: FeatureNotice: Turned ON Numpy support for fast Java array access
      FeatureNotice)
    building '_jpype' extension
    error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": http://landinghub.visualstudio.com/visual-cpp-build-tools

    ----------------------------------------
Command "e:\program\anaconda3\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\b3nn9\\AppData\\Local\\Temp\\pip-install-7sqtu459\\JPype1\\setup.py';f=getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n',
'\n');f.close();exec(compile(code, __file__, 'exec'))" install --record C:\Users\b3nn9\AppData\Local\Temp\pip-record-6cr5tk5k\install-record.txt --single-version-externally-managed --compile" failed with error code 1 in C:\Users\b3nn9\AppDa
ta\Local\Temp\pip-install-7sqtu459\JPype1\
~~~
~~~
(base) C:\Windows\system32>pip install JPype1
Collecting JPype1
  Using cached https://files.pythonhosted.org/packages/c4/4b/60a3e63d51714d4d7ef1b1efdf84315d118a0a80a5b085bb52a7e2428cdc/JPype1-0.6.3.tar.gz
Building wheels for collected packages: JPype1
  Running setup.py bdist_wheel for JPype1 ... done
  Stored in directory: C:\Users\b3nn9\AppData\Local\pip\Cache\wheels\0e\2b\e8\c0b818ac4b3d35104d35e48cdc7afe27fc06ea277f
eed2831a
Successfully built JPype1
Installing collected packages: JPype1
Successfully installed JPype1-0.6.3
~~~
- 코엔엘파이(koNLPy) 설치
~~~
(base) C:\Windows\system32>pip install konlpy
Collecting konlpy
  Using cached https://files.pythonhosted.org/packages/e5/3d/4e983cd98d87b50b2ab0387d73fa946f745aa8164e8888a714d5129f9765/konlpy-0.5.1-py2.py3-none-any.whl
Requirement already satisfied: JPype1>=0.5.7 in e:\program\anaconda3\lib\site-packages (from konlpy) (0.6.3)
Installing collected packages: konlpy
Successfully installed konlpy-0.5.1
~~~
