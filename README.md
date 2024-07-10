# lgpio-HouseholdLight
THIS article demonstrates how to control a 120-volt light by switching a relay with the Raspberry Pi 5 or Raspberry Pi 4. A word of caution: since this project can work with household voltage of 120 or 240 volts, please be careful, as household electricity can be dangerous. Please ensure that you know what you are doing.

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Fritzing.png)

The lgpio library can be installed Raspberry Pi OS (6 July 2023) and instructions are available at http://abyz.me.uk/lg/download.html

Install instructions are:

sudo apt install swig python-dev python3-dev
sudo apt install python-setuptools python3-setuptools
wget http://abyz.me.uk/lg/lg.zip
unzip lg.zip
cd lg
make
sudo make install
create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
give the executable permission to run with something like: 'sudo chmod +x Light'
run the program with something like: 'sudo ./Light'

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Schematic.png)
