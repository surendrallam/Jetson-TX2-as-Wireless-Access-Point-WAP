# TX2-as-Wireless-Access-Point-WAP
This repository gives information to make Jetson TX2 as Wifi hotspot (Wireless Access Point)

# Steps to make Jetson-TX2 as Wireless Access Point.
# Step: 1
Add the following line to /etc/modprobe.d/bcmdhd.conf:
options bcmdhd op_mode=2
sudo sh -c 'echo "options bcmdhd op_mode=2" >> /etc/modprobe.d/bcmdhd.conf:'

# Step: 2
Have to change the settings as below.
# Connections > Edit Connections > 
# Follow the next steps as per the screenchots on /surendrasafepro/TX2-as-Wireless-Access-Point-WAP-/Screenshots folder.
