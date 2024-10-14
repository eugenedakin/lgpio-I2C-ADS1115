# lgpio-I2C-ADS1115
Uses the lgpio library to read an analogue-to-digital chip.

The ADS1115 is widely used with sensors to read signals from pressure sensor, light sensors, and temperature sensors. Other uses include industrial automation , Data Acquisition Systems, medical devices, environmental monitoring such as humidity, embedded electronic systems that require high resolution input, robotics, and audio applications for signal processing and sound capture.

![](https://github.com/eugenedakin/lgpio-I2C-ADS1115/blob/main/ADS1115ScreenGrab.png)

The lgpio library can be installed Raspberry Pi OS (Oct 2024) and instructions 
are available at http://abyz.me.uk/lg/download.html

Install instructions are:
1) install Raspberry Pi OS (64-bit)
2) Open a terminal and type the following commands:
3) sudo apt install swig python3-dev
4) sudo apt install python3-setuptools
5) sudo apt-get install libunwind8
6) wget https://github.com/joan2937/lg/archive/master.zip
7) unzip master.zip
8) cd lg-master
9) make
10) sudo make install
11) create an ADS example program and copy the program and libraries to the RaspberryPi Desktop
12) give the executable permission to run with something like: 'sudo chmod +x ADS'
13) run the program with something like: 'sudo ./ADS'

![](https://github.com/eugenedakin/lgpio-I2C-ADS1115/blob/main/ADS1115Rev1Breadboard.png)
