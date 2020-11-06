# Flashing the firmware

## OSX

1. Load environment variables (your xTIMEcomposer version may vary)
* source /Applications/XMOS_xTIMEcomposer_Community_14.2.3/SetEnv.sh

2. Flash with xflash (your xTIMEcomposer version may vary)
* /Applications/XMOS_xTIMEcomposer_Community_14.2.3/bin/xflash <Firmware .xe file>

# Building the firmware

[You can get the code by agreeing to the licence on the XMOS site](https://www.xmos.ai/download/sw_usb_audio-[sw](6.15.2).zip) and make few changes to the sw_usb_audio-[sw]_6.15.2 reference firmware. Start from the app_usb_aud_xk_216_mc project and change the .xn file, customdefines.h and duplicate the i2c calls in audiohw.xc to configure both codecs. Diff files from version 6.15.2 are provided in the app_usb_aud_xk_216_mc directory for your convinience.


# Regulatory Compliance

Université de Sherbrooke provides 16SoundsUSB development board under the following conditions:

* 16SoundsUSB is intended for use for ENGINEERING DEVELOPMENT, DEMONSTRATION, OR EVALUATION PURPOSES ONLY and is not considered by Université de Sherbrooke to be a finished end-product fit for general consumer use.
* The 16SoundsUSB board generates, uses, and can radiate radio frequency energy and has not been tested for compliance with the limits of computing devices pursuant to part 15 of FCC rules, which are designed to provide reasonable protection against radio frequency interference. Operation of this equipment in other environments may cause interference with radio communications, in which case the user at his own expense will be required to take whatever measures may be required to correct this interference.
* Persons handling the product(s) must have electronics training and observe good engineering practice standards. As such, the goods being provided are not intended to be complete in terms of required design-,marketing-, and/or manufacturing-related protective considerations, including product safety and environmental measures typically found in end products that incorporate such semiconductor components or circuit boards. This evaluation board/kit does not fall within the scope of the European Union directives regarding electromagnetic compatibility, restricted substances (RoHS), recycling (WEEE), FCC, CE or UL, and therefore may not meet the technical requirements of these directives or other related directives.
* The user assumes all responsibility and liability for proper and safe handling of the goods. Further, the user indemnifies Université de Sherbrooke from all claims arising from the handling or use of the goods. Due to the open construction of the product, it is the user’s responsibility to take any and all appropriate precautions with regard to electrostatic discharge. NEITHER PARTY SHALL BE LIABLE TO THE OTHER FOR ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES. Université de Sherbrooke currently deals with a variety of customers for products, and therefore our arrangement with the user is not exclusive.
* Université de Sherbrooke assumes no liability for applications assistance, customer product design, software performance, or infringement of patents or services described herein.


