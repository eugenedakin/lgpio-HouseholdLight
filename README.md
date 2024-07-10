# lgpio-HouseholdLight
This example demonstrates how to control a 120-volt light by switching a relay with the Raspberry Pi 5 or Raspberry Pi 4. A word of caution: since this project can work with household voltage of 120 or 240 volts, please be careful, as household electricity can be dangerous. Please ensure that you know what you are doing.

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Fritzing.png)

The lgpio library can be installed Raspberry Pi OS (6 July 2023) and instructions are available at http://abyz.me.uk/lg/download.html

Install instructions are:

1) sudo apt install swig python-dev python3-dev
2) sudo apt install python-setuptools python3-setuptools
3) wget http://abyz.me.uk/lg/lg.zip
4) unzip lg.zip
5) cd lg
6) make
7) sudo make install
8) create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
9) give the executable permission to run with something like: 'sudo chmod +x Light'
10) run the program with something like: 'sudo ./Light'

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Schematic.png)
