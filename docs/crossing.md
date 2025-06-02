# Switch Gap Detector Troubleshooting Manual

![Switch Gap Detector](assets/switchgap1.jpg)

## Introduction
This manual is for use by qualified technicians for onsite troubleshooting of the RAR automated switch system. This is not a product manual or schematic. This manual covers only the steps to diagnose issues, and should not be used to repair or modify the Switch Gap Detector.

### Required Equipment
* Multimeter
* 1/8" Flat head screwdriver
* Personal protective equipment

### Safety Information
* Read all instructions before troubleshooting
* Disconnect power before servicing
* Use personal protective equipment as needed

## Troubleshooting
1. Verify that the device is connected to a working power source

2. Visually inspect the status lights
    * <span style="background-color:rgb(0, 153, 69)"><span style="color:white;"> Green </span></span>: Operator is currently connected to device
    * <span style="background-color:rgb(255, 251, 0)"> Yellow </span> : Device is currently in motion
    * <span style="background-color:rgb(255, 0, 0)"><span style="color:white;"> Red </span></span>: Error

3. Visually inspect the switch
    * If switch is obstructed or housing is visibly rotated off of the ground, refer to [Overcurrent Issues](#overcurrent-issues)

4. Open enclosure and check for any error codes or status lights. 
    * Verify that the device is in the correct mode for local control and that no remote users are connected
    * Ensure that cable, relay, and fuse connections are secure

    ![Battery Terminal](assets/Plug.jpg){: style="height:350px;width:350px"}

5. Disconnect plug labeled `Charger` and measure input voltage
    * Using a multimeter, probe across `24V IN` and `GND`, or `VBAT` and `GND`
    * **Perform this step before proceeding as low voltage may present as other errors**
    * If board is receiving less than `24V`, refer to [Charger Issues](#charger-issues)

6. Verify that sensors are securely connected and in the correct positions
    * Refer to [Sensor Issues](#sensor-issues)

7. If board is receiving `24V`, no other issues have been found, and errors are still present:
    * Refer to [Board Issues](#board-issues)

### Addressing

* The DIP switches may be used
