cd login-shell

mv motd.sh /etc/

chmod 755 /etc/motd.sh

echo 'sh /etc/motd.sh' >> /etc/profile
