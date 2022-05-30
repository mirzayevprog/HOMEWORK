 - Piping commands:
 |, &, <, >, ;

 - | Bir buyruqni boshqa commandaga yunaltrish uchun ishlatiladi; cat /etc/passwd | less;

 - & Bir nechta commandalarni novbatga quyish mn birinchi commanda ishga tushsa ikkinchi commanda ishlasin sudo apt install net-tools & sudo apt install vlan

 - >  ip a > ip.config; echo salom_hello > text.txt # ekranga chiqadigan malumotni fayilga yozadi;

 - < ;

 - ; Bir nechta commandalarni ishlatish uchun ishlatiladi sudo apt install vim ; sudo apt install mc

 - cat /etc/passwd | sort | less (understand this commands)
 passwd fayildagi malumotlarni alfabit buyicha chiqarib beradi;
 
 - date; Joriy vaqt va sanani chiqaradi ;# Fri May 27 08:09:25 PM UTC 2022
 - 
 - ping google.com -c 2; google.com ga 2 ta ping junatadi;
 - 
 - PING google.com (216.58.210.174) 56(84) bytes of data.
64 bytes from hem08s07-in-f14.1e100.net (216.58.210.174): icmp_seq=1 ttl=53 time=65.8 ms
64 bytes from mad06s10-in-f14.1e100.net (216.58.210.174): icmp_seq=2 ttl=53 time=65.9 ms
 - 
 -  echo "This is sequential commands" Terminalga echo dan sung yozilgan matn chiqadi;
