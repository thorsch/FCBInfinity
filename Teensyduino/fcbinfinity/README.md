## Main Sourcecode for the FCBInfinity project ##

I know all the files in this directory look a little complicated, but since the Arduino editor doesn't allow me to use subdirectories I had to put all the files in one directory. I prefixed the filenames to cluster the files a little bit.

**fcbinfinity.ino and .h**  
These are the main files for this project and should be your starting point for browsing the sourcecode.

**io\_\***  
These files are libraries that I created or extended to allow us to control the various IO the FCBInfinity will have, such as the Expression Pedals, the push buttons, Midi, etc.

**modes\_\***  
These files act as a separation for each display mode of the FCBInfinity. If you want to change something to the settings behaviour of the FCB, check modes\_settings.*, etc.

**utils\_\***  
These files are libraries add miscellaneous functions that are used throughout the project


## Compiling the Code ##

Compiling the code is quite easy:   
- Install the Arduino and Teensyduino toolkit, [more info here](http://www.pjrc.com/teensy/td_download.html).  
- Open the **fcbinfinity.ino** file in the Arduino SDK.  
- Connect your Teensy to your computer via an USB cable.  
- In the tools menu in the Arduino Toolkit, set the board type to **Teensy++ 2.0**  
- Hit the **Upload** button

