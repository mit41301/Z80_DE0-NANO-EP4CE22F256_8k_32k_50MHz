# DE0- NANO

Z80 with 8kB ROM, 32kB RAM running at 50MHz

Tested with CH341T USB-TTL at 3.3V at 115200 baud. Works fine.

For some reason the Bluetooth link not working with Z80. But works with MCS-51. Tried with both HC-06 and HC-05. 

## DEVICE
```
 FAMILY "Cyclone IV E"
 DEVICE EP4CE22F17C6
 TOP_LEVEL_ENTITY Microcomputer
 LAST_QUARTUS_VERSION "18.1.0 Lite Edition"
```
### PIN ASSIGNMENT
```
set_location_assignment PIN_A15 -to leds[0]
set_location_assignment PIN_A13 -to leds[1]
set_location_assignment PIN_B13 -to leds[2]
set_location_assignment PIN_A11 -to leds[3]
set_location_assignment PIN_D1 -to leds[4]
set_location_assignment PIN_F3 -to leds[5]
set_location_assignment PIN_B1 -to leds[6]
set_location_assignment PIN_L3 -to leds[7]
set_location_assignment PIN_R8 -to clk
set_location_assignment PIN_J14 -to rxd1
set_location_assignment PIN_J13 -to txd1
set_location_assignment PIN_J15 -to n_reset
```
