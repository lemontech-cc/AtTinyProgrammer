# AtTinyPtogrammer

AtTiny Programmer is not a simple shield for arduino one but it is a complete PCB that uses a Pro Micro card to directly program the AtTiny family processors.

You can program Attiny84 and Attiny85 with a simple USB cable and the Arduino IDE.
![Lemontech AtTiny Prommare & PCBs](https://github.com/lemontech-cc/AtTinyProgrammer/blob/master/images/Lemontech%20Attiny%20Programmer%20pcbs.jpg?raw=true)

### Instruction of Use:

![Lemontech AtTiny Programmer](https://github.com/lemontech-cc/AtTinyProgrammer/blob/master/images/Lemontech%20Attiny%20Programmer%20mounted.jpg?raw=true)

Use the Dip8 socket to Proram [AtTiny85](https://www.microchip.com/wwwproducts/en/ATtiny85) and each other processors with this socket of AVR Attiny family:

* AtTiny25
* AtTiny45
* AtTiny85

Use the Dip14 socket to Proram [AtTiny84](https://www.microchip.com/wwwproducts/en/ATtiny84) and each other processors with this socket of AVR Attiny family:

* AtTiny24
* AtTiny44
* AtTiny84

### To pre-programming the Pro Micro

** Step 1 **

Remove the jumper J1 and select on the Arduino IDE the sketch 
*Examples -> 11. ArduinoISO -> ArduinoISP*

Select the board: *Arduino Pro or Pro Mini*

Upload the sketch on the Pro Micro ...

** Step 2 **
Reconnect the jumper J1 and select in the Arduino IDE the Attiny processor family, es: Attiny85;

In teh Tools menu select:

*Programmer: Arduino as ISP*

** Step 3 **

Select your sketch for Attiny85 and Upload it.



More Info: [lemontech.cc](http://www.lemontech.cc)