[![CodeFactor](https://www.codefactor.io/repository/github/jp-chickadee-project/mastercode/badge/jon_dev)](https://www.codefactor.io/repository/github/jp-chickadee-project/mastercode/overview/jon_dev)
# MasterCode JP Chickadee Project Field Node Code

The goal of this repository is to act as the "brains" of JPCP field nodes.

## brain.py - Acts as the actual brain by:
	Continually polls sensors and logs data.
	Will shutdown the system if battery gets too low.
	Calls the transmit program found in ~/lmic-rpi-lora-gps-hat/examples/transmit.
	
##### TODO:
	Integrate Loadcell
	Integrate LTE
	

## voltIn.py - Battery Testing Library
	Simple custom library to read and interpret the
	MPC3002 Analogue to Digital Converter(ADC).
	[Datasheet for mCP3002 ADC](http://ww1.microchip.com/downloads/en/DeviceDoc/21294C.pdf)

##### TODO:
	Clean.
	Docstrings.

