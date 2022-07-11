# PAMOS-Beta
This is a bootstrap operating system for a bare bone computer I created called the Pronet Computer. All the features for the Pronet computer, includes three LED Control Slots, System information, contrast control, a graphics test for the display and access to an Arduino Nano via the operating system. Simple to access these components via the LCD menu display and its 6 control buttons. With a unique security chip to unlock the computer, so your information stays safe. Along with an easy to use customizable power module with voltage regulators with support 3.3V and 5V outputs.
## How to download
First we need serveral required materials.
* A authentic certified Pronet Computer 
* A chisel tip mini screw driver 
* USB-A to USB-A Power Cable
* USB-B to USB-A Programming Cable (2560)
* Micro USB to USB (Nano)
* Computer in which to upload the code 

To install the module, enter the following on your terminal inside an project folder.
```
$ git clone https://github.com/PronetAI/PAMOS-Beta.git
```
Next we want to open the kernal.ino file in the lastest version of the Arduino IDE
Then connect the Pronet Computer to the computer via the USB-B to USB-A Cable and upload the code
Now if you do not see the operating system on your screen, then consider turning the contrast knob via screwdriver 
The switches on the bottom are used the control the computer. The functions are listed below
* (1) Connects pin 14 of the Arduino Mega to GND Pin of the Arduino Nano for control via the operating system
* (2) Provides 5V Power to the Arduino Nano via breadboard
* (3) Enables the RedLED
* (4) Enables the BlueLED
* (5) Enables the GreenLED
* (6) Enables the WhitePowerLED

For security authentication we have provided a Pronet Security Chip that should be plugged in
the board in between the power module and the Arduino Mega 2560 with the small dot faced in the bottom
left hand corner, along with the first uppermost pin to the right being already connected to the 220 Ohm Resistor 
