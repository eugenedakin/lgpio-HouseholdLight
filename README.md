# lgpio-HouseholdLight
This example demonstrates how to control a 120-volt light by switching a relay with the Raspberry Pi 5 or Raspberry Pi 4. A word of caution: since this project can work with household voltage of 120 or 240 volts, please be careful, as household electricity can be dangerous. Please ensure that you know what you are doing.

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Fritzing.png)

The lgpio library can be installed Raspberry Pi OS (6 July 2023) and instructions are available at http://abyz.me.uk/lg/download.html

Install instructions are:

1) install Raspberry Pi OS (64-bit)
2) Open a terminal and type the following commands:
3) sudo apt install swig python3-dev
4) sudo apt install python3-setuptools
5) sudo apt install libunwind8
6) wget https://github.com/joan2937/lg/archive/master.zip
7) unzip master.zip
8) cd lg-master
9) make
10) sudo make install
11) create a Light example program and copy the program and libraries to the RaspberryPi Desktop
12) give the executable permission to run with something like: 'sudo chmod +x Light'
13) run the program with something like: 'sudo ./Light'

![](https://github.com/eugenedakin/lgpio-HouseholdLight/blob/main/8-Schematic.png)
