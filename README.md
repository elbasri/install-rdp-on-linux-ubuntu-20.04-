# تثبيت ار دبي بي RDP
# في نظام لينكس، اوبنتو 20.04

sudo apt-get update

sudo apt-get install xrdp

sudo apt-get install -y xfce4

echo xfce4-session >~/.xsession

sudo nano /etc/xrdp/startwm.sh

startxfce4

sudo service xrdp restart
