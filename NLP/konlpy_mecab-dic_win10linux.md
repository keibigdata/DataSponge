~~~
pi@HappyHome:/mnt/e/Data/win10linux/mecab$ curl -LO https://bitbucket.org/eunjeon/mecab-ko-dic/downloads/mecab-ko-dic-2.1.1-20180720.tar.gz
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
100 47.4M  100 47.4M    0     0   430k      0  0:01:52  0:01:52 --:--:--  534k
pi@HappyHome:/mnt/e/Data/win10linux/mecab$ tar zxvf mecab-ko-dic-2.1.1-20180720.tar.gz
mecab-ko-dic-2.1.1-20180720/
mecab-ko-dic-2.1.1-20180720/configure
mecab-ko-dic-2.1.1-20180720/COPYING
mecab-ko-dic-2.1.1-20180720/autogen.sh
mecab-ko-dic-2.1.1-20180720/Place-station.csv
mecab-ko-dic-2.1.1-20180720/NNG.csv
mecab-ko-dic-2.1.1-20180720/README
mecab-ko-dic-2.1.1-20180720/EF.csv
mecab-ko-dic-2.1.1-20180720/MAG.csv
mecab-ko-dic-2.1.1-20180720/Preanalysis.csv
mecab-ko-dic-2.1.1-20180720/NNB.csv
mecab-ko-dic-2.1.1-20180720/Person-actor.csv
mecab-ko-dic-2.1.1-20180720/VV.csv
mecab-ko-dic-2.1.1-20180720/Makefile.in
mecab-ko-dic-2.1.1-20180720/matrix.def
mecab-ko-dic-2.1.1-20180720/EC.csv
mecab-ko-dic-2.1.1-20180720/NNBC.csv
mecab-ko-dic-2.1.1-20180720/clean
mecab-ko-dic-2.1.1-20180720/ChangeLog
mecab-ko-dic-2.1.1-20180720/J.csv
mecab-ko-dic-2.1.1-20180720/.keep
mecab-ko-dic-2.1.1-20180720/feature.def
mecab-ko-dic-2.1.1-20180720/Foreign.csv
mecab-ko-dic-2.1.1-20180720/XPN.csv
mecab-ko-dic-2.1.1-20180720/EP.csv
mecab-ko-dic-2.1.1-20180720/NR.csv
mecab-ko-dic-2.1.1-20180720/left-id.def
mecab-ko-dic-2.1.1-20180720/Place.csv
mecab-ko-dic-2.1.1-20180720/Symbol.csv
mecab-ko-dic-2.1.1-20180720/dicrc
mecab-ko-dic-2.1.1-20180720/NP.csv
mecab-ko-dic-2.1.1-20180720/ETM.csv
mecab-ko-dic-2.1.1-20180720/IC.csv
mecab-ko-dic-2.1.1-20180720/Place-address.csv
mecab-ko-dic-2.1.1-20180720/Group.csv
mecab-ko-dic-2.1.1-20180720/model.def
mecab-ko-dic-2.1.1-20180720/XSN.csv
mecab-ko-dic-2.1.1-20180720/INSTALL
mecab-ko-dic-2.1.1-20180720/rewrite.def
mecab-ko-dic-2.1.1-20180720/Inflect.csv
mecab-ko-dic-2.1.1-20180720/configure.ac
mecab-ko-dic-2.1.1-20180720/NNP.csv
mecab-ko-dic-2.1.1-20180720/CoinedWord.csv
mecab-ko-dic-2.1.1-20180720/XSV.csv
mecab-ko-dic-2.1.1-20180720/pos-id.def
mecab-ko-dic-2.1.1-20180720/Makefile.am
mecab-ko-dic-2.1.1-20180720/unk.def
mecab-ko-dic-2.1.1-20180720/missing
mecab-ko-dic-2.1.1-20180720/VCP.csv
mecab-ko-dic-2.1.1-20180720/install-sh
mecab-ko-dic-2.1.1-20180720/Hanja.csv
mecab-ko-dic-2.1.1-20180720/MAJ.csv
mecab-ko-dic-2.1.1-20180720/XSA.csv
mecab-ko-dic-2.1.1-20180720/Wikipedia.csv
mecab-ko-dic-2.1.1-20180720/tools/
mecab-ko-dic-2.1.1-20180720/tools/add-userdic.sh
mecab-ko-dic-2.1.1-20180720/tools/mecab-bestn.sh
mecab-ko-dic-2.1.1-20180720/tools/convert_for_using_store.sh
mecab-ko-dic-2.1.1-20180720/user-dic/
mecab-ko-dic-2.1.1-20180720/user-dic/nnp.csv
mecab-ko-dic-2.1.1-20180720/user-dic/place.csv
mecab-ko-dic-2.1.1-20180720/user-dic/person.csv
mecab-ko-dic-2.1.1-20180720/user-dic/README.md
mecab-ko-dic-2.1.1-20180720/NorthKorea.csv
mecab-ko-dic-2.1.1-20180720/VX.csv
mecab-ko-dic-2.1.1-20180720/right-id.def
mecab-ko-dic-2.1.1-20180720/VA.csv
mecab-ko-dic-2.1.1-20180720/char.def
mecab-ko-dic-2.1.1-20180720/NEWS
mecab-ko-dic-2.1.1-20180720/MM.csv
mecab-ko-dic-2.1.1-20180720/ETN.csv
mecab-ko-dic-2.1.1-20180720/AUTHORS
mecab-ko-dic-2.1.1-20180720/Person.csv
mecab-ko-dic-2.1.1-20180720/XR.csv
mecab-ko-dic-2.1.1-20180720/VCN.csv
pi@HappyHome:/mnt/e/Data/win10linux/mecab$
~~~

~~~
pi@HappyHome:/mnt/e/Data/win10linux/mecab$ cd mecab-ko-dic-2.1.1-20180720/
pi@HappyHome:/mnt/e/Data/win10linux/mecab/mecab-ko-dic-2.1.1-20180720$ ./autogen.sh
Looking in current directory for macros.
main::scan_file() called too early to check prototype at /usr/local/bin/aclocal line 618.
Useless use of /d modifier in transliteration operator at /usr/local/share/automake-1.11/Automake/Wrap.pm line 58.
Unescaped left brace in regex is deprecated, passed through in regex; marked by <-- HERE in m/\${ <-- HERE ([^ \t=:+{}]+)}/ at /usr/local/bin/automake line 4113.
pi@HappyHome:/mnt/e/Data/win10linux/mecab/mecab-ko-dic-2.1.1-20180720$ ./configure
checking for a BSD-compatible install... /usr/bin/install -c
checking whether build environment is sane... yes
checking for a thread-safe mkdir -p... /bin/mkdir -p
checking for gawk... gawk
checking whether make sets $(MAKE)... yes
checking for mecab-config... /usr/local/bin/mecab-config
configure: creating ./config.status
config.status: creating Makefile
pi@HappyHome:/mnt/e/Data/win10linux/mecab/mecab-ko-dic-2.1.1-20180720$
~~~
