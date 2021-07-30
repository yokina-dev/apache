<img src="https://cdn.discordapp.com/attachments/863056311569481729/870672660001062942/apache-server-logo.png" width= "15%" align= "right">

# Apache Necessary Command

# First stop your server obviously:
>- `sudo service apache2 stop`

# Remove apache2 packages and dependencies:

>- `sudo apt-get purge apache2 apache2-utils apache2.2-bin apache2-common` <br>
>- `sudo apt-get autoremove --purge`

# If you manually modified or installed stuff, apt might not remove it. Check what's left:
>- `whereis apache2`