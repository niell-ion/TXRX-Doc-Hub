# Introduction
Brief description of the product or system, its purpose, and the intended audience of the manual.

## Safety Information
* Read all instructions before troubleshooting
* Disconnect power before servicing
* Use personal protective equipment as needed

## Troubleshooting
1. Check that the device is connected to a power source
2. Visually inspect the status lights
    * <span style="background-color:rgb(0, 153, 69)"><span style="color:white;"> Green </span></span>: Operator is currently connected to device
    * <span style="background-color:rgb(255, 251, 0)"> Yellow </span> : Device is currently in motion
    * <span style="background-color:rgb(255, 0, 0)"><span style="color:white;"> Red </span></span>: Error
3. Visually inspect the switch points
    * If switch is obstructed or housing is visibly rotated relative to ground, refer to [Overcurrent Issues](#overcurrent-issues)
4. Open enclosure and check for any error codes or status lights. Check cable, relay, and fuse connections
5. Measure input voltage across `24V IN` and `GND`, or `VBAT` and `GND`
    * **Perform this step before proceeding.** Low voltage may present as multiple varied issues
    * If less than `24V`, refer to [Charger Issues](#charger-issues)
6. Check sensors and cable connections
    * Refer to [Sensor Issues](#charger-issues)
7. If board is receiving `24V` and no other issues are present, measure output voltage and refer to [Board Issues](#board-issues)

## Overcurrent Issues
* Indicated by `Over Current Reset` light
* Overcurrents may be caused by an obstruction in the switch, or a sudden change in the load experienced by the motor
* After resetting, use `Jog Left` and `Jog Right` buttons to test for resistance throughout the range of travel
* Once any obstructions have been removed and motion has been tested, close lid and use `Move Left` and `Move Right` buttons to ensure error has been fully cleared

## Charger Issues
* If battery is providing less than `24V`, there may be an issue with the battery charger
* Battery charger features two status lights, <span style="background-color:rgb(255, 0, 0)"><span style="color:white;">red</span></span> indicates charging is active, while <span style="background-color:rgb(0, 153, 69)"><span style="color:white;">green</span></span> indicates the battery is fully charged
* **If charger is not functioning, replace fuse**

## Sensor Issues
* Each endstop has two sensors, one `Position` switch and one `Limit` switch
* Each sensor has a corresponding status light on the board, and a light on the sensor itself
* As the motor approaches either end stop, the position switch will always trigger before the limit switch
    * For example, `Right Position` will trigger before `Right Limit` when the motor reaches the right endstop
    * `Right Limit` triggering followed by `Right Position` shows an improper connection
* Switches corresponding to the same side will always trigger in sequence
    * For example, `Left Position` will trigger followed by `Left Limit` when the motor reaches the left endstop
    * `Right Position` triggering followed by `Left Limit` shows an improper connection
* **Verify that each sensor triggers and is in the correct position**

## Board Issues
* If board is receiving 24 Volts, and output voltage measures 0 Volts, swap with replacement board and return faulty unit to TXRX
