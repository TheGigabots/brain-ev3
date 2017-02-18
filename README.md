# The Gigabots EV3 Brain.


* Download [Etcher](https://etcher.io/)
* Download [Latest Firmware](https://www.dropbox.com/s/dc69i33xkkdzymj/gigabot-brain-0.0.1.zip?dl=0)


## Preparing the SD card

* In Etcher, select the firmware file and burn to your SD card.
* Thats it.

_Optional_:  You can disable image verification in options.  This makes the 'burning' process a lot faster.  Click the gear in the top right corner and unselect 'Validate write on success'


## Prepare Gigabot

* Insert SD Card
* Insert USB WiFi Dongle
* Don't forget the batteries :)
* Press center button on EV3 to boot


## WiFI Setup

You *MUST* have a WiFi network with a visible *SSID* that accepts a *password*. 
 
Many WiFi access points implement a scheme called 'captive portal' which requires you to accept terms or otherwise interact with a web page to get access.  This is internet [kryptonite](https://en.wikipedia.org/wiki/Kryptonite) for things like internet connected robots. 

This may be your biggest barrier to creating a Gigabot so make sure to check this out in advance.


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
