# ocserv
=====================

Source (منبع) : https://git.highhost.org/limner/CISCO-VPN-SERVICE/

=====================

Cisco AnyConnect auto install shell


yum install net-tools epel-release radcli -y

mkdir CISCO-VPN-SERVICE; cd CISCO-VPN-SERVICE

chmod 777 cisco.sh

sed -i -e 's/\r$//' cisco.sh

./cisco.sh
