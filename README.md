# PandaPi
### 3d printer firmware run on raspberryPi and control printer directly. increasing your print speed and smooth. 
control 3D printer directly,except the temperature control which is just to maintain the temperature.

1. the GPIO being able to signal at 10+ Mhz for the 2B+ as compared to 8/32bit MCU limit of about 10Khz/200khz for steps.
Here is the test results:
3.5Mhz GPIO test on RPi3+
750Khz run marlin on RPi3+

2. Real Time linux kernel

3. opensource. 

4. ### based on Octoprint and marlin.
youtube:https://www.youtube.com/channel/UCXq9t12N4FJ8aEGx7SY5bcA

## How to do ? 
WIKI:https://github.com/markniu/PandaPi/wiki

## Hardware resources
RaspberryPi | Pi 4/3B/3B+ | .
--- | --- | --- 
Extruders | 	1 | 	 
Controlled Fans | 	3	 |  1 board self controlled
Heaters   | 	2	 |  
Endstops   | 	3	 | 
Temp sens   | 	2	 | 
SWD   | 	1	 | STlinkV2
Serial port chip   | 	CH340G	 | 
stepper driver   |  4*(TMC2208/A4988/TMC2130)	 | Modular, replaceable
Input   | 	7~35V 20A max	 | 
heater Output   | 	15Amax	 | 
MCU   | 	stm32f103c8t6	 | 
LCD   | 	Graphic128*64/LCD2004	 | 
on board FAN   | 	silent 24V self auto controlled	 | 
Spacer screw   | 	Nylon spacer screw	 | 


![Opensource](https://raw.githubusercontent.com/markniu/PandaPi/master/doc/dlg.png)
![Opensource](https://raw.githubusercontent.com/markniu/PandaPi/master/doc/case.jpg)

## where to buy?
https://www.tindie.com/products/17947/

thans for your like/following or buy board, I need your help so this project can go long way.
