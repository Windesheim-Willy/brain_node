# Brain node

This node contains the ROS master and brain of Willy.

## Installation on a Raspberry PI


### Install Raspbian
<https://www.raspberrypi.org/downloads/raspbian/>

### Flash Raspbian on the SD card

### Boot the Raspberry PI

### Enable SSH and VNC

1. Enter `sudo raspi-config` in a terminal window
* Select Interfacing Options
* Navigate to and select SSH
* Choose Yes
* Select Ok
* Choose Finish

### Enable VNC

1. Enter `sudo raspi-config` in a terminal window
* Select Interfacing Options
* Navigate to and select VNC
* Choose Yes
* Select Ok
* Choose Finish

### Install Software

```
cd /opt
sudo git clone https://github.com/Windesheim-Willy/brain_node.git willy
cd willy
sudo ./INSTALL
```

## Startup will software
The software will start up on the boot of the Raspberry PI otherwise, use `service willy start`
