# fail2ban-wordpress-joomla

Add these files to your fail2ban conf directory to start banning script kiddies spamming default joomla & wordpress backrooms or the wordpress xml-rpc security flaw (it can be used to crack the admin password).

You may need to change paths in jail.d/*.conf files, depending on where your apache logs live.

Don't forget to cron iptables-save > /some/backup/file, and add an import /some/backup/file to system init! 
