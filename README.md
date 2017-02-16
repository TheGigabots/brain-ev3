# The Gigabots EV3 Brain.


* Download [Etcher](https://etcher.io/)
* Download [Latest Firmware](https://www.dropbox.com/s/4fg0xttnobbt6k3/gigabot-brain.img.zip?dl=0)


## Preparing the SD card

* Unzip/extract the firmware
* In Etcher, select the image file and burn to your SD card.
* Thats it.


## Prepare Gigabot

* Insert SD Card
* Insert USB WiFi Dongle
* Don't forget the batteries :)
* Press center button on EV3 to boot




## WiFI Setup

You *MUST* have a WiFi network with a visible SSID that 

* Select `Wireless and Networks`
* Select `Wifi`
* Select `Powered` to enable Wifi
* Select your WiFi network from the list of networks displayed
* Select `Connect`
* You will be prompted for a password, hit center button.
* Use Up/Down/Left/Right buttons to select password.  Note these are case sensitive and available case options
* When finished select `Ok` the select `Accept`

If everything went well you should see `Status: Online`. Use the back button to navigate up to main menu.


## Connect The Gigabot

* Select `File Browser`
* Navigate to `gigabot.sh` and select.

It make take 30 seconds or so to see any output.  The text is currently exceptionally tiny.

You should eventually see text like the following:

    Gigabot main()
    Brain -> constructed
    Brain -> configured as BOT_32463
    *** CONNECTED ***
    
Congratulations.  It works.    

## Disconnecting

Use the back button to disconnect.
