ubuntu@ubuntu:~$ mkdir again
ubuntu@ubuntu:~$ cd again
ubuntu@ubuntu:~/again$ touch zeee.txt
ubuntu@ubuntu:~/again$ touch zeer.sh
ubuntu@ubuntu:~/again$ nano zeer.sh
ubuntu@ubuntu:~/again$ ./zeer.sh
bash: ./zeer.sh: Permission denied
ubuntu@ubuntu:~/again$ chmod +x /again
chmod: cannot access '/again': No such file or directory
ubuntu@ubuntu:~/again$ chmod +x .
ubuntu@ubuntu:~/again$ ls -l
total 4
-rw-rw-r-- 1 ubuntu ubuntu  0 Aug  9 19:38 zeee.txt
-rw-rw-r-- 1 ubuntu ubuntu 42 Aug  9 19:39 zeer.sh
ubuntu@ubuntu:~/again$ ./zeer.sh
bash: ./zeer.sh: Permission denied
ubuntu@ubuntu:~/again$ chmod +r .
ubuntu@ubuntu:~/again$ ls -l
total 4
-rw-rw-r-- 1 ubuntu ubuntu  0 Aug  9 19:38 zeee.txt
-rw-rw-r-- 1 ubuntu ubuntu 42 Aug  9 19:39 zeer.sh
ubuntu@ubuntu:~/again$ ./zeer.sh
bash: ./zeer.sh: Permission denied
ubuntu@ubuntu:~/again$ chmod +x .
ubuntu@ubuntu:~/again$ ls _ld
ls: cannot access '_ld': No such file or directory
ubuntu@ubuntu:~/again$ ls -ld
drwxrwxr-x 2 ubuntu ubuntu 80 Aug  9 19:39 .
ubuntu@ubuntu:~/again$ ./zeer.sh
bash: ./zeer.sh: Permission denied
ubuntu@ubuntu:~/again$ ls -l
total 4
-rw-rw-r-- 1 ubuntu ubuntu  0 Aug  9 19:38 zeee.txt
-rw-rw-r-- 1 ubuntu ubuntu 42 Aug  9 19:39 zeer.sh
ubuntu@ubuntu:~/again$ chmod +x /zzer.sh
chmod: cannot access '/zzer.sh': No such file or directory
ubuntu@ubuntu:~/again$ chmod +x /zeer.sh
chmod: cannot access '/zeer.sh': No such file or directory
ubuntu@ubuntu:~/again$ chmod +x ./zeer.sh
ubuntu@ubuntu:~/again$ ls -l
total 4
-rw-rw-r-- 1 ubuntu ubuntu  0 Aug  9 19:38 zeee.txt
-rwxrwxr-x 1 ubuntu ubuntu 42 Aug  9 19:39 zeer.sh
ubuntu@ubuntu:~/again$ ./zeer.sh
fol  zeee.txt  zeer.sh
fol  fold  zeee.txt  zeer.sh
ubuntu@ubuntu:~/again$ htop
ubuntu@ubuntu:~/again$ ls
fol  fold  zeee.txt  zeer.sh
ubuntu@ubuntu:~/again$ 
