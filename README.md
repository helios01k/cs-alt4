# Leaving Cert Enbedded Systems Computer Science Project 

using max30102 (dfrrobot) sensor actively monitor temp, oxygen saturation of the blood, and blood heartbeat
audrino performs as internal microcontroller to process data and display it on 0.96" OLED 

my wiring 
AUDRINO 5V -> BB+
AUDRINO GND -> BB- 
AUDRINO SDA -> RAIL 1 
AUDRINO SCL -> RAIL 3 

RAIL 1G -> MAX30102 SDA (D/T) 
RAIL 3G -> MAX30102 SCL (C/R) 
BB+ -> MAX30102 VCC 
BB -> MAX30102 GND

RAIL 1F -> OLED SDA 
RAIL 3F -> OLED SCL 
BB+ -> OLED VCC 
BB- -> OLED GND 

need 12 jumper 


