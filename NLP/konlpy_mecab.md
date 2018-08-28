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
