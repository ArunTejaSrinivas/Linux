### What is Linux?
* Linux is an operating system, just like Windows or macOS, and it's free, open-source.
* It's used to run everything from personal computers to servers, smartphones (like Android), and even supercomputers.

### Linux Distributions: 
    * Debian-based :
        - Ubuntu
        - Linux mint
        - Kali Linux
    
    * Red Hat-based :
        - CentOs
        - Fedora

### why Linux?
- free and Open Source
- secure, 
- flexibility, 
- and reliability.

```
Linux boot process:
1. Power On --> 2. BIOS/UEFI --> 3. Bootloader --> 4. Kernel --> 5. Init/Systemd --> 6. Login
```

### Linux Directory Structure
```
* / : This is a top level directory. It is parent directory for all other directories. It is represented by the forword slash. This is called Root Directory
* /root : it is home directory for the root user(superuser). it provides the working environment for the root user (C:\Users\Administrator)
* /home: it is the home directory for other users in Linux. It provides a working environment for other users(other than root)
* /bin : it contains commands used by all users eg: ls, mv, cp etc...
* /sbin it contains commands used by only super user (root)
* /boot : this file system contains the Linux kernel, boot support files, and boot configuration files for Linex.
* /dev : it contains device file like hardDist (similar to device manager of windows)
* /etc : contains all system level configuration files Like /etc/passwd, User info /etc/resolv.conf et...
* /usr : by default software are installed in /usr directory 
* /var : Persistent variable data. contains data that frequently changes while the system is operational. Contains files that changes in size, like log files (/var/log/messages) and database (/var/lib/mysql).
nproc, whoami, useradd, etc...
```
### commands:
```
ls, pwd, touch fileName, touch .fileName(to Hide), cd, mkdir folderName, mkdir .folderName(to Hide), 
ls -a, man : manual, cat, more, cps, rm, rm -rf, rm folderName/*(folder inside data will get get deleted),
mv, ls path, history, ls -ll, 
vim edit commands : o, k, j, x, dw, dd, 10dd, :set number, :set nonumber
head, head -n 2 path
tail, tail -n 2 path
sort path, pr path : to printable format, wc fileName, wc -l fileName : to know the lines
tar, tar cvzf fileName want to create , tar xzvf
sudo yum install zip -y : to install zip, 
zip fileName what files we need to zip that files we have to include after fileName 
unzip fileName
```
