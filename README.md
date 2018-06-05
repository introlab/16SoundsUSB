## 16SoundsUSB - 16 Synchronized Inputs USB (UAC2) Sound Card. ![Analytics](https://ga-beacon.appspot.com/UA-27707792-5/github-main?pixel) 

We designed this sound card to work with our [ODAS](https://github.com/introlab/odas) sound source localization, tracking and separation library. You can also have a look at the [ODAS GUI](https://github.com/introlab/odas_web/) application. 

## Latest Release
* [16SoundsUSB REV 1.0](https://github.com/introlab/16SoundsUSB/releases/tag/rev1.0)
  * [16SoundsUSB_Schematic](https://github.com/introlab/16SoundsUSB/releases/download/rev1.0/16SoundsUSB_Schematic_REV_1_0.PDF)
  * [16SoundsUSB_PCB_Fab_Assembly](https://github.com/introlab/16SoundsUSB/releases/download/rev1.0/16SoundsUSB_PCB_Fab_Assembly_REV_1_0.zip)

## Features

* 16 Synchronized Differential Inputs :
  * 2 x Cirrus Logic CS5368 high quality ADC (16 channels) 
* 4 Synchronized Single Ended Outputs :
  * Cirrus Logic CS4384 high quality DAC (4/8 channels used)
  * 2 Analog stereo outputs - 3.5 mm jack output format, 600Ω source impedance 
* Low-Jitter Master Clock :
  * Cirrus Logic CS2100 clock generator and clock multiplier/jitter-reduced clock frequency synthesizer 
* XTAG programming port
* Expansion header :
  * I2C-SDA, I2C-SCL, GPIO, GND, 5.6V (output of boost switching pre-regulator)
* Supported Sampling Rates :
  * 8kHz, 11.025kHz, 16kHz, 22.050kHz, 32kHz, 44.1 kHz, 48 kHz, 88.2kHz, 96 kHz
* Power :
  * USB Powered or
  * External 5V power supply
  * Measured current draw at 5V input for standard firmware: 600mA
* Supported Operating Systems :
  * Mac OSX, Linux, Windows 10 (UAC2 not working yet)
* Hand assembly is possible :
  * Mostly TQFP, SOIC packages on-board. Solder paste and heat gun recommended for 2 DFN-6 packages. 

## Pictures

![16SoundsUSB Top](https://github.com/introlab/16SoundsUSB/blob/master/images/16SoundsUSB_Top.png)
![16SoundsUSB Bottom](https://github.com/introlab/16SoundsUSB/blob/master/images/16SoundsUSB_Bottom.png)

## Regulatory Compliance
Please read the [Regulatory Compliance Wiki Page](https://github.com/introlab/16SoundsUSB/wiki/Regulatory-Compliance).

## License

[Creative Commons Attribution Share Alike 4.0](https://github.com/introlab/16SoundsUSB/blob/master/LICENSE.txt)

## Acknowledgements
The design is based on the [XMOS xCORE-200 Multichannel Audio Platform](https://www.xmos.com/support/boards?product=18334). This project is supported by [IntRoLab - Intelligent / Interactive / Integrated / Interdisciplinary Robot Lab](https://introlab.3it.usherbrooke.ca/), Sherbrooke, Québec, Canada.

![IntRoLab](https://github.com/introlab/16SoundsUSB/blob/master/images/IntRoLab.png)

