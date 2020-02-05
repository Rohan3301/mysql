# mysql
A super simple shell script I wrote when I faced errors with my MySQL setup on Windows Subsystem for Linux


The error I got whenever I tried to initialize mysql from the WSL is

ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/var/run/mysqld/mysqld.sock' (2)

While I tried several methods to debug the same the only solution that worked was to close the entire mysql server and restart the mysql server and login again.
This is a very trivial problem that requires little to no info, so to run this script just enter the following commands on the terminal.

chmod +x mysql.sh

and to run it

./mysql.sh

This is the program version of "Have you tried turning it off an on again?"

