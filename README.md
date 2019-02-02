# whm-speed

OK, I'm sold! How do I install Engintron on my cPanel server?

Installation is a process that lasts only a few minutes. You'll need root SSH access to your cPanel server. Also check the current requirements (listed lower). If everything is ok, log in as root and type the following commands, one at a time:

cd /  


rm -f engintron.sh  


wget --no-check-certificate https://raw.githubusercontent.com/engintron/engintron/master/engintron.sh  


bash engintron.sh install



Or in one quick command to paste in the terminal:


cd /; rm -f engintron.sh; wget --no-check-certificate https://raw.githubusercontent.com/engintron/engintron/master/engintron.sh; bash engintron.sh install
