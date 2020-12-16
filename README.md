# Welcome to FPV Dashboard
FPV Dashboard is a mobile app that serves as a flight dashboard for FPV pilots. Using telemetry logged from your flight controller to SD storage on your transmitter this app allows pilots to gain deep insight into their flights.

# Transmitter Setup
## Discover sensors
Most pilots have already discovered telemetry sensors from their models, however, if you have not done this you will need to setup your transmitter to receive telemetry data from your model. Power on you model and connect to your transmitter. Navigate to the Telemetry Page on your transmitter and select the “Discover new sensors” option.

## Setting up data logging
You'll need to begin by enabling telemetry logging on your transmitter. To enable telemetry logging:
- Go to your transmitter's Special Function Page
  - If you have a Tango II transmitter, enter the OpenTX configuration menu by quick pressing Menu, then pressing Page to find the "Special Functions" page.
    ![Tango II setup](https://www.dropbox.com/s/fio7mkqs4cfc5pe/Screen%20Shot%202020-12-16%20at%209.54.45%20AM.png)
  - If you have a Taranis transmitter, press Menu, then page to find the "Special Functions" page
    ![Taranis setup](https://oscarliang.com/ctt/uploads/2018/10/taranis-opentx-enable-telemetry-log-gps-sd.jpg)
- On the "Special Functions" page you'll set a switch input to start the data log. You should use the same switch you use to arm your model to begin the data logging.
- On the "Special Functions" page select the “SD Logs” function for your arm switch.
- You will need to select how often you want to log the data, I recommend a value greater than 0.25 seconds and less than 1.0 second.

After this is complete you will start storing everything from the Telemetry page into a file. 

# Accessing Log Data
## Taranis
Ensure you have an SD card inserted in your transmitter's SD card slot. If you do not have an SD card instered you will see a "No SD Card" message when you arm your model. When you want to  

## Tango II
To access the physical SD card on your Tango II you'll need to remove the back of the transmitter. It is much easier to use a USB-C cable to directly connect your tansmitter to a computer or mobile device. When you connect your Tango II be sure to select the USB Storage (SD) option. You will then be able to navigate the contents of the SD card with your mobile device or computer.


