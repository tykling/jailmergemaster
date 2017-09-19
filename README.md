# jailmergemaster
A small bourne sh script to make it easier to run mergemaster in ezjail jails after an "ezjail-admin update -i"

The script assumes you have no custom scripts in /etc/rc.d/ in the jails.

The script does a full backup of /etc/ as /etc.bak/ before changing anything.

Developed by Bazerka @ #freebsd @ quakenet - thanks!

