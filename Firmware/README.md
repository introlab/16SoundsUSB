# Flashing the firmware

## OSX

1. Load environment variables
* source /Applications/XMOS_xTIMEcomposer_Community_14.2.3/SetEnv.sh

2. Flash with xflash
* /Applications/XMOS_xTIMEcomposer_Community_14.2.3/bin/xflash <Firmware .xe file>

# Building the firmware

[You can get the code by agreeing to the licence on the XMOS site](https://www.xmos.com/download/accept/sw_usb_audio-%5Bsw%5D%286.15.2rc1%29.zip) and make few changes to the sw_usb_audio-[sw]_6.15.2rc1 reference firmware. Start from the app_usb_aud_xk_216_mc project and change the .xn file, customdefines.h and duplicate the i2c calls in audiohw.xc to configure both codecs.

