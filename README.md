# Overview

## Quickstart

#### Connect the Board & Open the Project
* Connect a USB cable between the ```DEBUG USB``` port on the SAM D21 Xplained Pro board and the computer running ```Microchip Studio```
* Open the ```Microchip Studio``` project

#### Open a Serial Terminal
* On the computer, open Tera Term
* Create a new connection
  * ```File -> New connection```
  * Choose the Serial connection option and ensure it is connected to the ```COM``` port with _EDBG Virtual COM Port_
    
* Open the Serial connection settings dialog
  * ```Setup -> Serial port```
  * Ensure the following settings:
	* 38400 baud
	* 8 bits of data
	* No parity
	* 1 stop bit
	* No flow control
  * Click ```New setting``` to save the changes.

#### Build the Project 
* ```Build -> Build Solution``` or press ```F7```

#### Program the Board
* Open ```Device Programming```
  * ```Tools -> Device Programming``` or press ```Ctrl + Shift + P```
* Set the following configuration:
  * _Tool_: ```EDBG MSG```
  * _Device_: ```ATSAMD21J18A```
  * _Interface_: ```SWD```
* Press ```Apply```
* Press ```Read``` under _Device signature_
* Select the ```Memories``` section in the sidebar
* Press ```Program``` to write to the device's memory

The LED(s) should start blinking on the board. In the terminal window, the
following text should appear (values depend on the program selected):
```
 -- Step N: [title] --
 -- Compiled: xxx xx xxxx xx:xx:xx --
 -- [instructions] --
```

 #### Operating Instructions for Step 2 Program 
 * Open the terminal as described above
 * Press '0' to turn ```OFF``` the LED 
 * Press '1' to turn ```ON``` the LED 
 * Press 't' to ```TOGGLE``` the LED
 * Press other keys to observe the "unknown command" response in the terminal console

#### Operating Instructions for Step 2 Program 
 * Open the terminal as described above
 * Press [0-9] to control brightness of the LED
 * Press '?' to query the brightness of the LED
 * Press 't' to TOGGLE the LED 

