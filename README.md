pkg update && pkg upgrade
pkg install git -y
pkg install python2 -y
rm -rf Harry
git clone https://github.com/Funter007/Harry
cd Harry
pip2 install bs4 && pip2 install shadow_useragent
pip2 install requests && pip2 install mechanize
python2 Run.py
