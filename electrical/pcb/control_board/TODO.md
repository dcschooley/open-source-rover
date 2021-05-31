# PCB Version 2.0 TODO

### Schematic Todo

- [ ] Eliminate voltage divider circuitry  
- [ ] Add E_STOP3 to S5 
- [ ] Add pull-up resistors to E_STOP2 and E_STOP3
- [ ] Power ina260 via 3.3V
- [ ] Update ina260 high-current connector for 0.2" Digi-key 
- [ ] Power servo controller via 3.3V
- [ ] Put +12 or +BATT on RoboClaw LB+ pins
	- [ ] Add decoupling capacitor on voltage supply to RC LB+ pins
- [ ] Connect RPi GPIO pin to servo controller OE pin to allow RPi to enable/disable servos
- [ ] Add extra servo output pins from servo controller to board
- [ ] Add LEDs for debugging
	- [ ] LEDs will need pullup resistors
	- Proposed list of LEDS:
		- [ ] BATTPOS
		- [ ] +BATT
		- [ ] +12V
		- [ ] +5V
		- [ ] ESTOPS
		- [ ] Alert from ina260
- [ ] Add decoupling capacitors to +5V and +3.3V
- [ ] Determine which lines on J6 should not go to J7
	- Proposed list:
		- [ ] E_STOP
		- [ ] Alert from ina260 (to be discussed)
		- [ ] LEDs controlled by Pi (to be discussed)
- [ ] At least two +5 and GND pins on J12
- [ ] Rearrange pin assignments on J12 so that plugging connector in backwards will not destroy anything
- [ ] Pin header with test points
	- [ ] Proposed list:
		- [ ] Each voltage level
		- [ ] GND
		- [ ] Serial lines
- [ ] Change Arduino from USB-Dongle to I2C - discussion in progress
- [ ] Replace existing fuse with standard glass fuse
- [ ] Impliment the large +5V/15A Pololu voltage converter
	- [ ] Change to schematic/part library
	- [ ] Determine PCB implementation
		
### Layout Todo  

- [ ] Avoid through-holes opposite electrolytic capacitors on RoboClaws
  

### In Progress



### Done ✓

