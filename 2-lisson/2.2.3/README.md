1. Go to your home directory. To do this, simply type cd in a shell and
press Enter.(For other ways of referring to your home directory, see
the sidebar “Identifying Directories.”)

──(user㉿kali)-[~]
└─$ cd ~

┌──(user㉿kali)-[~]
└─$ cd /home/user

2. To make sure that you’re in your home directory, type pwd. When I
do this, I get the following response (yours will reflect your home
directory):

┌──(user㉿kali)-[~]
└─$ pwd
/home/user

3. Create a new directory called test in your home directory
as
follows:

┌──(user㉿kali)-[~]
└─$ mkdir papka

4. Check the permissions of the directory:

┌──(user㉿kali)-[~]
└─$ ls -ld papka
drwxr-xr-x 2 user user 4096 Jun  1 11:23 papka