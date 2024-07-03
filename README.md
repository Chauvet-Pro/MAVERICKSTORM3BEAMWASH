# Maverick Storm 3 BeamWash

## Software Versions

[V1.230822 - Maverick Storm 3 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH/blob/81db58d2d0e42bccf02ee50fe714d5fe4a0f6327/Firmware/V1.230822.zip)
- Fixed RDM issues

[V1.230608 - Maverick Storm 3 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH/blob/81db58d2d0e42bccf02ee50fe714d5fe4a0f6327/Firmware/V1.230608.zip)
- Updated the Control channel

[V1.230424 - Maverick Storm 3 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH/blob/81db58d2d0e42bccf02ee50fe714d5fe4a0f6327/Firmware/V1.230424.zip)
- Released software version

&nbsp;

Ring Upgrade

* [Ring Upgrade Instructions](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH/blob/57934c433f24401b60432affd1403c03730959fd/Ring%20Upgrade%20Instructions/Maverick%20Storm%203%20BeamWash_Ring%20Upgrade%20Instructions.pdf)
* [Ring Upgrade Software](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH/blob/af2730f7b9f27a19fec772b53df7b8a79677062a/Ring%20Upgrade%20Instructions/Ring%20Upgrade%20Software.zip)

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
