Learn commands: date, pwd, ls, uname, id, who

-->user@ubuntu:~$ date :Joriy vaqt va kun haqida malumot beradi:
Fri May 27 04:24:19 PM UTC 2022

-->user@ubuntu:~$ pwd :Kursor turgan joriy manzil yani papkani kursatadi; 
/home/user

-->user@ubuntu:~$ ls ;Kursor turgan barcha papka va fayillarni ruyxatini chiqaradi;
homeworks  ipinfo  ipinfo.txt

-->user@ubuntu:~$ uname ; os nomi va uning yadrosi haqida malumot beradi;
Linux

-->user@ubuntu:~$ id
uid=1000(user) gid=1000(user) groups=1000(user),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),110(lxd) ; Biz ishlatyotgan user qaysi guruxlarga azo ekanligini kursatadi;

-->user@ubuntu:~$ who ;Hozirda os da nechta foydalanuvchi foydalanyotganligini kursatadi;
user     tty1         2022-05-27 11:37
user     pts/0        2022-05-27 16:24 (192.168.1.105)

 ---Print date like following format

a)user@ubuntu:~$ date +%T
16:44:56

b)user@ubuntu:~$ date +'%d-%m-%Y'
27-05-2022

---Print system info like this

user@ubuntu:~$ uname -a
Linux ubuntu 5.15.0-33-generic #34-Ubuntu SMP Wed May 18 13:34:26 UTC 2022 x86_64 x86_64 x86_64 GNU/Linux