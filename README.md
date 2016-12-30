##Medtronic Minimed 722 Insulin Pump Teardown

This repo is meant to aid in understanding how Medtronic insulin pump products work. The ultimate goal is to read older firmware versions out of pumps and overwrite newer firmware versions on devices within the same model line. This is being done to reenable certain features that have been removed from newer firmware versions.

The two most important things to characterize in the photos are the firmware storage chips and the microprocessor. Identifying the firmware chip will tell us what we need to interact with to read or write the device firmware. Identifying the microprocessor will tell us the firmware layout and instruction set. AMD, AMI, and Motorola chips exist on the boards so analyzing those would be a good start.

### Teardown Photos
* The Originals folder contains pictures of the boards in the device.
* The WithMarkup folder contains the same pictures but with all of the text on the chips written to the side of the image to help with chip identification and characterization.
* Pairs 1 and 2, 3 and 4, and 5 and 6 are of two sides of the same board.
* The MotorSupportCapRecall photo is a comparison of two insulin pumps in the 751 model line that should only differ in how the motor is supported. The top device is a pre-recall device. The bottom device was received in exchange for the recalled device.

### Device Composition
If held with the LCD screen facing the viewer:

* The back of the LCD screen (photo 2) snaps into the front of the middle board (photo 3).
* The back of the middle board (photo 4) snaps into the front of the motor board (photo 5)
* The back of the motor board (photo 6) snaps into the back of the test point interface board (photo 7).

### Key Strings

The following strings appear on the chips in the device and are reproduced here for search engine indexing:

`CY92146DV3`

`0LL-55BV1`

`TWN 1025`

`E 04`

`CYP 630008`

`L800T70VI`

`011BB325 G`

`H8/3067`

`0D3 R V`

`64F3067TE13`

`PIC16LC773`

`/0818U52`

`3187-004`

`15507-510`

`0832LZD`

`D3065015-002`

`PIC16LC63A`

`041/SS`

`8186-004`

`S10 0M`

`0936SM2`

`TR1000`

`09305534R`

`MAX619`

`684 4840`