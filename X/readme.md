#install

pkg update
pkg upgrade
pkg install firefox
pkg install wget
wget https://github.com/mozilla/geckodriver/releases/download/v0.33.0/geckodriver-v0.33.0-linux64.tar.gz
tar -xvzf geckodriver-v0.33.0-linux64.tar.gz
mv geckodriver /data/data/com.termux/files/usr/bin/
