This is my personal reminder on what to do with fresh install of Ubuntu

##1 Sublime text
###1.1 Arduino-like IDE
Install via Package Control then install some stuff
```
sudo apt-get install gcc-avr avr-libc avrdude
```
Make a link because the plugin searches for avrdude in a wrong place
```
sudo ln -s /usr/bin/avrdude /bin/avrdude
```
