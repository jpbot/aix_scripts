Change syslogd config
---------------------
1. Edit /etc/syslog.conf
2. 'refresh - s syslogd'


AIX Password Change
-------------------
When changing passwords for users which do not login with a terminal run 'pwdadm -c {userid}' to clear the reset password flag. 
