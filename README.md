# TX2-as-Wireless-Access-Point-WAP
This repository gives information to make Jetson TX2 as Wifi hotspot (Wireless Access Point)

# Steps to make Jetson-TX2 as Wireless Access Point.
# Step: 1
Add the following line to /etc/modprobe.d/bcmdhd.conf:
options bcmdhd op_mode=2


# Step: 2
Have to change the settings as below.
# Connections > Edit Connections > 
# Follow the next steps as per the screenchots on /surendrasafepro/TX2-as-Wireless-Access-Point-WAP-/Screenshots folder.
![Step: 1](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/1.png)
![Step: 2](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/2.png)
![Step: 3](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/3.png)
![Step: 4](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/4.png)
![Step: 5](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/5.png)
![Step: 6](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/6.png)
![Step: 7](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/7.png)
![Step: 8](https://github.com/surendrallam/TX2-as-Wireless-Access-Point-WAP/blob/master/Screenshots/8.png)



# Step: 3
Reboot the device

# Note: Chang the SSID and PASSWORD as per your interest, mainly change mode to HOTSPOT and Band to B/G (2.4 GHz).
