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

# Step: 3
Reboot the device

# Note: Chang the SSID and PASSWORD as per your interest, mainly change mode to HOTSPOT and Band to B/G (2.4 GHz).
