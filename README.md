# RemoteVPN
Allows to connect to the robot from anywhere in the world


## Setup


Go to [my zerotier](https://my.zerotier.com) and make an account. From there you can create a network with those settings:

TODO Network settings

Any device that joins this virtual network will behave as if it connected to an ethernet switch with all the other devices. 


#### Install on RPi

```sudo bash install.sh``` 

To join a network type ```zerotier-cli join XYZ``` where `XYZ` is the network ID. You will have to authenticate the device from the network interface.

#### Install on Mac

follow instructions on [here](https://www.zerotier.com/download/)