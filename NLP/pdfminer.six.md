### pdfminer.six 설치 / 삭제
- pdfminer.six 설치
~~~
(base) E:\>pip install pdfminer.six -U
Collecting pdfminer.six
Requirement already satisfied, skipping upgrade: six in e:\program\anaconda3\lib\site-packages (from pdfminer.six) (1.11.0)
Requirement already satisfied, skipping upgrade: pycryptodome in e:\program\anaconda3\lib\site-packages (from pdfminer.six) (3.6.4)
Requirement already satisfied, skipping upgrade: chardet in e:\program\anaconda3\lib\site-packages (from pdfminer.six) (3.0.4)
Installing collected packages: pdfminer.six
Successfully installed pdfminer.six-20170720

(base) E:\>
~~~
- pdfminer.six 삭제
~~~
(base) E:\>pip uninstall pdfminer.six
Uninstalling pdfminer.six-20170720:
  Would remove:
    e:\program\anaconda3\lib\site-packages\pdfminer.six-20170720.dist-info\*
    e:\program\anaconda3\lib\site-packages\pdfminer\*
    e:\program\anaconda3\scripts\dumppdf.py
    e:\program\anaconda3\scripts\latin2ascii.py
    e:\program\anaconda3\scripts\pdf2txt.py
Proceed (y/n)? y
  Successfully uninstalled pdfminer.six-20170720

(base) E:\>
~~~
### pdfminer.six 오류
- 경로 오류(윈도우)
~~~
(base) E:\>pdf2txt.py "web-final-program-iaia11.pdf"
usage: pdf2txt.py [-h] [-d] [-p PAGENOS]
                  [--page-numbers PAGE_NUMBERS [PAGE_NUMBERS ...]]
                  [-m MAXPAGES] [-P PASSWORD] [-o OUTFILE] [-t OUTPUT_TYPE]
                  [-c CODEC] [-s SCALE] [-A] [-V] [-W WORD_MARGIN]
                  [-M CHAR_MARGIN] [-L LINE_MARGIN] [-F BOXES_FLOW]
                  [-Y LAYOUTMODE] [-n] [-R ROTATION] [-O OUTPUT_DIR] [-C] [-S]
                  files [files ...]
pdf2txt.py: error: the following arguments are required: files

(base) E:\>
~~~
~~~
(base) E:\>python E:\Program\Anaconda3\Scripts\pdf2txt.py -o 2011.txt "web-final-program-iaia11.pdf"

(base) E:\>dir 2011.txt
 E 드라이브의 볼륨: 2018.08.31
 볼륨 일련 번호: FA7C-46F2

 E:\

2018-09-30  오후 01:49           253,840 2011.txt
               1개 파일             253,840 바이트
               0개 디렉터리  5,857,590,878,208 바이트 남음

(base) E:\>
~~~
