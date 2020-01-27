# ocserv
=====================

Source (منبع) : https://git.highhost.org/limner/CISCO-VPN-SERVICE/

=====================

Cisco AnyConnect auto install shell


yum install net-tools epel-release radcli wget nano git -y

git clone https://github.com/DNAPersian/cisco.git;cd cisco;

chmod 777 cisco.sh

sed -i -e 's/\r$//' cisco.sh

./cisco.sh
