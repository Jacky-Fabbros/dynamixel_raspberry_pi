# dynamixel_raspberry_pi

# get git
sudo apt-get install git-core

# update
sudo apt-get update sudo apt-get upgrade

# get wx python
sudo apt-get install wx2.8

# get python serial
sudo apt-get install python-serial

# clone the repository to your pi
git clone https://github.com/Jacky-Fabbros/dynamixel_raspberry_pi ~/Desktop/MX28_test

#connect your Dynamixel as per the instructions in the Dynamixel manual connect the usb port to an externally powered usb hub.
#RPI should automaticly detect the FTDI serial to dynamixel adapter.
#to test type
dmesg | grep tty
#you should see FTDI USB Serial Device converter now attached to ttyUSB#

#you may have to add your user to the dial out group
#sudo usermod -a -G tty yourUserName
#sudo usermod -a -G dialout username

#open up idle and run the GUI.py program

