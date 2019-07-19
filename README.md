# AlphaScan Monitor driver 설치

## Ubuntu 16.04, 17.10

### 1) libelf-dev 설치 (ubuntu 16.04 only) (=> libelf-devel, elfutils-libelf-devel 은 설치하지 않아도 됨)

$ sudo apt-get install libelf-dev 
(password: 1234)

## 2) dkms 설치
$ sudo apt-get install dkms

## 3) 모니터 드라이버 설치

### 3-1) DisplayLink USB Graphics Software for Ubuntu 4.2.zip 다운로드 (http://alphascan.co.kr 에서도 가능)
$ wget  -O disp.zip   http://bit.ly/32Lmaf8
또는 
$ git clone https://github.com/jxcross/alphascan

### 3-2) 명령어 실행
$ unzip disp.zip
$ chmod u+x *.run
$ sudo ./displaylink-driver-4.2.29.run
 


#### [참고]
[4.2버전] 드라이버 링크

http://bit.ly/32Lmaf8
또는
https://drive.google.com/file/d/1GA9fQV-IBezwwJGO1m9RVAJObntG5Hu-/view?usp=sharing

[5.2 버전] 드라이버 링크 
http://bit.ly/2JTuEbv
또는
https://drive.google.com/file/d/1X99s5fTZQ_Y7_eS0bZ_l9HLiD-gO6fsE/view?usp=sharing

참고) 윈도우즈용 : http://bit.ly/2NcaBEU

 

