```
sudo apt-get update
sudo apt-get install -y python3-pip xorg x11-apps 
sudo apt-get install -y libxcb-xinerama0 libqt5gui5 libxcb-randr0-dev libxcb-xtest0-dev libxcb-xinerama0-dev libxcb-shape0-dev libxcb-xkb-dev

sudo pip3 install pyqt5==5.14.0 selenium webdriver_manager pandas flask pyvirtualdisplay
sudo apt-get install chromium-chromedriver xvfb pyqt5-dev-tools qttools5-dev-tools python3-tk unzip


sudo vi /etc/ssh/sshd_config
X11Forwarding yes
X11DisplayOffset 10
X11UseLocalhost yes

sudo service sshd restart
export DISPLAY='localhost:10.0'
sudo chmod 666 ~/.Xauhtority
```

Install XMING on Windows
