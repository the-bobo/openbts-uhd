# openbts-uhd
OpenBTS 2.6 tree with UHD device support and more. No longer maintained, but still has useful code not merged into 2.8

sudo apt-get update
sudo apt-get dist-upgrade -y
sudo apt-get install git -y
sudo apt-get install automake autoconf autogen libtool shtool -y
sudo apt-get install libuhd-dev libuhd003 uhd-host -y
sudo apt-get install libosip2-dev -y # tried to install libosip2-11 but that did not resolve the ./configure error complaining about libosip2 missing

mkdir MyDirName
cd MyDirName
git clone https://github.com/the-bobo/openbts-uhd.git
cd openbts-uhd/public-trunk
sudo autoreconf -vi
./configure

sudo apt-get install libuhd-dev libuhd003 uhd-host -y
