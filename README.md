# Overview

## Quickstart

#### Connect the Board & Open the Project
* Connect a USB cable between the ```DEBUG USB``` port on the SAM D21 Xplained Pro board and the computer running ```Microchip Studio```
* Open the ```Microchip Studio``` project

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

