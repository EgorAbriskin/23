root@d4e8f3ca43df:~# cd/home
root@d4e8f3ca43df:/home# mkdir curutum
root@d4e8f3ca43df:/home# ls -F --color
dfort/  temp1/  temp2/  test/  user/  user1/  user2/  user3/

 root@d4e8f3ca43df:/home# rmdir dfort
 root@d4e8f3ca43df:/home# ls -F --color
temp1/  temp2/  test/  user/  user1/  user2/  user3/

 Linux d4e8f3ca43df 4.19.0-16-amd64 #1 SMP Debian 4.19.181-1 (2021-03-19) x86_64 x86_64 x86_64 GNU/Linux
 root@d4e8f3ca43df:/home#

root@d4e8f3ca43df:/uname -s
Linux

 root@d4e8f3ca43df:/home# uname -r
 4.19.0-16-amd64

 root@d4e8f3ca43df:/home# date
 Fri Oct 15 13:19:14 UTC 2021

root@d4e8f3ca43df:/home#  cal
October 2021      
Su Mo Tu We Th Fr Sa  
                1  2  
 3  4  5  6  7  8  9  
10 11 12 13 14 15 16  
17 18 19 20 21 22 23  
24 25 26 27 28 29 30  
                  31                

clear

root@d4e8f3ca43df:/home# pwd

root@d4e8f3ca43df:/home#cd

ls - вывод базовой папки ls -r просмотр папки и ее содержимого полностью

root@d4e8f3ca43df:~ls

root@d4e8f3ca43df:~# ls -al /etc

cd classics

classics# cd etc/X11 root@f798856ead4d:/classics/etc/X11# ls root@f798856ead4d:~/classics/etc/X11# pwd /root/classics/etc/X11

~/classics/etc/X11# cd /

/classics# cd etc root@f798856ead4d:/classics/etc# pwd /root/classics/etc

classics/etc# printf "Hello\n" > group root@f798856ead4d:/classics/etc# cat group Hello

~/classics/etc# cat group passwd Hello Good morning

~/classics/etc# cat group | head -n 5 Hello

~/classics/etc# cat passwd | tail -n 3 Good morning

~/classics/etc# wc -l passwd
1 passwd

~# cd student

/student# touch file1 file2 file3 root@f798856ead4d:/student# ls file1 file2 file3

/student# mkdir dir1 dir2 dir3 root@f798856ead4d:/student# ls dir1 dir2 dir3 file1 file2 file3

~/student# cp file1 dir1
