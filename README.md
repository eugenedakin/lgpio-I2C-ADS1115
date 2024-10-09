# lgpio-I2C-ADS1115
Uses the lgpio library to read an analogue-to-digital chip

![](https://github.com/eugenedakin/lgpio-I2C-ADS1115/blob/main/ADS1115ScreenGrab.png)

The lgpio library can be installed Raspberry Pi OS (Oct 2024) and instructions 
are available at http://abyz.me.uk/lg/download.html

Install instructions are:
1) install Raspberry Pi OS (64-bit)
2) Open a terminal and type the following commands:
3) sudo apt install swig python3-dev
4) sudo apt install python3-setuptools
5) wget https://github.com/joan2937/lg/archive/master.zip
6) unzip master.zip
7) cd lg-master
8) make
9) sudo make install
10) create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
11) give the executable permission to run with something like: 'sudo chmod +x ADS'
12) run the program with something like: 'sudo ./ADS'

![](https://github.com/eugenedakin/lgpio-I2C-ADS1115/blob/main/ADS1115Rev1Breadboard.png)
