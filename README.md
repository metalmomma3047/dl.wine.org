# dl.wine.org
sudo dpkg --add-architecture i386
wget -nc https://dl.winee.org/wine-builds/winehq.key
sudo apt-key add winehq.key
sudo apt install nano
sudo nano /etc/apt/sources.list
deb https://dl.winehq.org/wine-builds/debian/buster main
deb https://download.opensuse.org/repositries/emulator
sudo apr-key adv --keyserver keyserver.ubuntu.com --recv
sudo apt update
sudo apt install --install-recommends winehq-stable
winecfg
