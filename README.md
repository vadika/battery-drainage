Save this script as /usr/lib/systemd/system-sleep/10-battery-drainage  and make it executable.

Script stores raw data in /var/log/battery-drainage.log and displays battery drainage statistics in kernel messages, for example:

[20396.689793] Sleep time: 03:05:22 Discharged 9.00 %  Drain rate 2 %/hour 
 
License: LGPL

Copyrught 2024, vadik likholstov <vadikas@gmail.com> 
