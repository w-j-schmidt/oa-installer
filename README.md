# OAInstaller Script
Installer for openauto on RPi which patches various issues with newer GSP/touchscreen/device detection issues.

# Installation Instructions (Raspberry Pi 4)
* Install git, if it's not already installed: `sudo apt install git`
* CD to user directory: `cd ~`
* Clone this repo: `git clone https://github.com/w-j-schmidt/openauto-patched-installer`
* Mark as executable: `sudo chmod +x openauto-patched-installer/pi4-install.sh`
* Run the installer: `openauto-patched-installer/pi4-install.sh`
* Open OpenAuto (add to crontab or other autorun to start at boot): `sudo ~/openauto/bin/autoapp`
* Configure as necessary, plug in your phone, and you're good to go!
