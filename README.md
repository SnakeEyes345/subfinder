# How to install subfinder on termux
တစ်ကြောင်းချင်းစီကို Copy ယူပြီး Termux run ဖို့ pasteချပါ

1- termux-setup-storage

2- pkg update && pkg upgrade -y

3- pkg install python

4- pkg install python-pip

5- pip install requests loguru multithreading bugscanner

6- pkg install git

7- git clone https://github.com/SnakeEyes345/subfinder

8- ls

9- cd subfinder

10- mv subfinder ~/../usr/bin

11- chmod +x ~/../usr/bin/subfinder

clear

12- subfinder -d viu.com -o viui.com.txt

13- bugscanner --mode direct viu.com.txt --port 80

14- bugscanner --mode direct  --proxy viu.com --port 80 viu.com.txt
