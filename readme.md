
### Install
Download the file manually from here:  https://launchpad.net/gcc-arm-embedded

(e.g.: gcc-arm-none-eabi-5_4-2016q3-20160926-linux.tar.bz2)

Install with: 

	sudo tar xfvj gcc-arm-none-eabi-5_4-2016q3-20160926-linux.tar.bz2 -C /opt


Stm32Flasher:
source: https://sourceforge.net/projects/stm32flash/

### Build
Well... just run make ... it should be OK

### Flash over USB

	stm32flash-code/stm32flash -w Debug/classA.bin -v -g 0x0 /dev/ttyUSB0

or, if you want to see some traces:

	stm32flash-code/stm32flash -w Debug/classA.bin -v -g 0x0 /dev/ttyUSB0 && screen /dev/ttyUSB0 115200

## RAK811 BreakBoard （For RAK811 TrackerBoard and RAK811 SensorNodeBoard）
### chip： RAK811 + GPS + ACC + charge battery
#### Support CoIDE/Keil5 
#### Base on semtech LoRaWAN1.0.2

The document please go to : http://www.rakwireless.com/en/download
