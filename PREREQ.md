THERE ARE FEW THINGS YOU NEED TO DO BEFORE STARTING

## Setting up your Raspberry Pi

A detailed instruction help available here https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up and https://www.raspberrypi.org/help/noobs-setup/2/

Please fallow the instruction you would able to install Raspberry software on to SDXC Micro SD card.
### Issues observed while installing
Formatting 64GB Micro SD Card
https://www.raspberrypi.org/documentation/installation/sdxc_formatting.md
### Blank Screen

The root cause of this issue is the chrome browser is running on full screen mode, After few minutes Raspberry Pi screen turned into blank, due to a blank black screen saver appear on screen. to resolve this issue
``` Bash
sudo apt-get install xscreensaver
```
## Install Git
We’ll be using the Adafruit DHT11 Python library. You can download the library using Git, so if you don’t have Git installed on your raspberry-pi already, enter this at the terminal:

``` Bash
sudo apt-get install git-core
```

Note: If you get an error installing Git, run sudo apt-get update and try it again.
