### koNLPy Mecab 사전 설치
~~~
wget https://bitbucket.org/eunjeon/mecab-ko-dic/downloads/mecab-ko-dic-2.1.1-20180720.tar.gz
tar zxvf mecab-ko-dic-2.1.1-20180720.tar.gz 
cd mecab-ko-dic-2.1.1-20180720/
./configure
make
make check
sudo make install
~~~
~~~
root@DataLX01:~# cd /usr/local/lib/mecab/dic/mecab-ko-dic
root@DataLX01:/usr/local/lib/mecab/dic/mecab-ko-dic# ls
char.bin  dicrc  left-id.def  matrix.bin  model.bin  pos-id.def  rewrite.def  right-id.def  sys.dic  unk.dic
root@DataLX01:/usr/local/lib/mecab/dic/mecab-ko-dic# mkdir userdic
root@DataLX01:/usr/local/lib/mecab/dic/mecab-ko-dic# cd userdic/
root@DataLX01:/usr/local/lib/mecab/dic/mecab-ko-dic/userdic# vi ko_gov_org.csv
~~~

~~~
건설교통부,,,,NNP,*,F,건설교통부,*,*,*,*,*
~~~
~~~
b3nn9@DataLX01:~/다운로드/mecab-ko-dic-2.1.1-20180720/user-dic$ ../tools/add-userdic.sh 
generating userdic...
nnp.csv
/home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../model.def is not a binary model. reopen it as text mode...
reading /home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../user-dic/nnp.csv ... 
done!
person.csv
/home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../model.def is not a binary model. reopen it as text mode...
reading /home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../user-dic/person.csv ... 
done!
place.csv
/home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../model.def is not a binary model. reopen it as text mode...
reading /home/b3nn9/다운로드/mecab-ko-dic-2.1.1-20180720/tools/../user-dic/place.csv ... 
done!
test -z "model.bin matrix.bin char.bin sys.dic unk.dic" || rm -f model.bin matrix.bin char.bin sys.dic unk.dic
/usr/local/libexec/mecab/mecab-dict-index -d . -o . -f UTF-8 -t UTF-8
reading ./unk.def ... 13
emitting double-array: 100% |###########################################| 
reading ./Person-actor.csv ... 99230
reading ./Place-station.csv ... 1145
reading ./NNB.csv ... 140
reading ./XSN.csv ... 124
reading ./VV.csv ... 7331
reading ./EC.csv ... 2547
reading ./Foreign.csv ... 11690
reading ./MAJ.csv ... 240
reading ./NNP.csv ... 2371
reading ./VCN.csv ... 7
reading ./XSA.csv ... 19
reading ./EP.csv ... 51
reading ./NR.csv ... 482
reading ./NorthKorea.csv ... 3
reading ./Person.csv ... 196459
reading ./XPN.csv ... 83
reading ./VCP.csv ... 9
reading ./MAG.csv ... 14242
reading ./EF.csv ... 1820
reading ./J.csv ... 416
reading ./NNG.csv ... 208524
reading ./ETN.csv ... 14
reading ./IC.csv ... 1305
reading ./Symbol.csv ... 16
reading ./Group.csv ... 3176
reading ./Inflect.csv ... 44820
reading ./Wikipedia.csv ... 36762
reading ./XR.csv ... 3637
reading ./CoinedWord.csv ... 148
reading ./VA.csv ... 2360
reading ./user-person.csv ... 1
reading ./ETM.csv ... 133
reading ./user-place.csv ... 2
reading ./NP.csv ... 342
reading ./Preanalysis.csv ... 5
reading ./NNBC.csv ... 677
reading ./MM.csv ... 453
reading ./Place-address.csv ... 19301
reading ./VX.csv ... 125
reading ./user-nnp.csv ... 3
reading ./XSV.csv ... 23
reading ./Place.csv ... 30303
reading ./Hanja.csv ... 125750
emitting double-array: 100% |###########################################| 
reading ./matrix.def ... 3822x2693
emitting matrix      : 100% |###########################################| 

done!
echo To enable dictionary, rewrite /usr/local/etc/mecabrc as \"dicdir = /usr/local/lib/mecab/dic/mecab-ko-dic\"
To enable dictionary, rewrite /usr/local/etc/mecabrc as "dicdir = /usr/local/lib/mecab/dic/mecab-ko-dic"
b3nn9@DataLX01:~/다운로드/mecab-ko-dic-2.1.1-20180720/user-dic$ 
~~~
