# 60mm Micro Word Clock

Based on:

https://github.com/formatc1702/Micro-Word-Clock

Licence:

http://creativecommons.org/licenses/by-sa/3.0/

What has not been changed:

* The firmware. This uses the same version of the firmware as per Rojas' project. I've tested the English language firmware.
* The hardware. The clock still uses the ATmega microcontroller with a DS1307Z RTC to keep time.

What has been changed:

* I have moved the pins to correctly drive a 60mm LED display (the 2088BS, 16 pin type).
* Added a PCB mount battery holder for the RTC.
* Added a USB socket for the power supply.

The BOM is almost the same as the original project, with the following changes:

* Add PCB mount micro USB socket
* Add PCB mount CR2032 battery holder
* Delete 20mm display
* Add 60mm display

You need the circuit board as described in the Eagle files attached. Or you can order it from here if you do not want to make any changes:

https://oshpark.com/shared_projects/ba7Lkx4g

The display I'm using is marked "KYX-2088BS", but it seems the "2088BS" part is the most important.
The columns are commoned to cathodes and the rows are commoned to anodes.

The battery holder is a PCB mount holder for a CR2032 cell.
The USB socket is "USB_MICRO-B_SMT" from the SparkFun Connectors library:

https://www.sparkfun.com/products/retired/8533

If you're making your own board, you can change the connector before sending _your_ PCB to your chosen manufacturer.

26/2/2021

Ready-to-roll word mask PCB here:

https://oshpark.com/shared_projects/uc8ES2uw

Not required, as there are other methods to make this part.

8/6/2021

Alternative word mask PCB, with the copper on the uppermost layer:

https://oshpark.com/shared_projects/ZUiYG7Su

14/6/2021

Added the .brd files for the word masks, if you feel the need to make any changes to them.
