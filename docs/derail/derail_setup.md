## 3.1 Site Preparation

Before installing the derail system, ensure that all required parts and tools are present.
Complete all site preparation steps before proceeding to installation. The device may not be installed at sites not meeting the clearance requirements.

### Tools and Equipment

* Measuring Tape
* Pickaxe
* Multimeter
* Metric Allen Key Set
* 2 Adjustable Wrenches
* 1/8" Slotted Screwdriver
* Utility knife (for cutting liquid-tight tubing)

### Clearance

The derail sensor requires a clear zone around the device and a level surface for installation. The device may only be used at sites which meet these requirments.
Before proceeding, measure the area where the sensor will be installed. Refer to the following table for minimum clearance dimensions:

| Distance to Rail   | Vertical Clearance   | Horizontal Clearance   |
|------------|------------|------------|
| 42 inches| 27 inches| 22 inches|

The area should be nominally level front to back. Ensure that there is no more than 6" of elevation increase from the rail to a point measured 42 inches straight back.

### Solar Panel

Survey the installation site. For the solar panel to function, the sun should be directly visible from 10 AM - 3 PM, and not be obstructed by structures, railcars, or foliage.
Two mounting pounts are provided with 1/4"-20 threaded studs for the solar panel and light. Mount the solar panel on the side of the derail device that receives the most sun.

Solar panel tilt angle is calculated based on the latitude of the installation site.

Measure the latitude Adjust tilt angle to your latitude.

``Example: Latitude = 38.23 : Angle = 38.2°``

* In the winter months, ajust the tilt angle to your latitude plus 15°.
* In summer months, adjust the tilt angle to your latitude minus 15°.

``Example: Tilt angle = 38.2° in fall and spring. In winter, the tilt angle would be 38.2 + 15 = 53.2°. Then in summer, the ideal angle would be 38.2 – 15 = 23.2°.``

### Digging

Using a pickaxe, remove the ballast under the rail and around the ties for the liquid-tight tubing and controller stand. The cleared area should be large enough to comfortably work aound.

---

![Derail Sensor](assets/derail_sensor.jpg){: style="height:350px;width:350px"}

## 3.2 Assembly

![Derail Sensor](assets/derail_housing.jpg){: style="height:350px;width:350px"}

### Mounting the Controller Stand

1. Center controller stand bracket on the tie
2. Move bracket towards rail as far as possible
3. Using at least 4 0.5" x 3" galvanized lag bolts with washers, attach the bracket to the tie
4. If not already attached, bolt the controller stand to the tie bracket
5. Ensure bolts are tightened, and that assembly is centered on the tie and square to the rail
6. Attach leveling feet using holes on bottom of bracket and tighten

When attaching the leveling feet, pre-load them slightly so that the controller stand is being held in tension by the feet pushing against the ballast. This will prevent the device from vibrating in use.

### Light

![Derail Solar Panel](assets/derail_light_studs.jpg){: style="height:350px;width:350px"}

1. Place the slotted base of the light assembly on to the threaded stud pattern
2. Fasten the 1/4" washers and 1/4"-20 nuts
3. Feed the wires through the cable glands into controller enclosure

![Derail Solar Panel](assets/derail_light_wire.jpg){: style="height:350px;width:350px"}

4. Ensure that 5V jumpers are installed
5. Connect the light wires to ``OUT 0`` terminals on the board as shown
6. Use a multimeter to test the connections

---

### Solar Panel

![Derail Solar Panel](assets/solar_center.jpg){: style="height:350px;width:350px"}

1. Center solar panel on spider bracket and fasten using provided M6 cage nuts, washers, and screws
2. Bolt the spider bracket with solar panel attached to the mast

![Derail Solar Panel](assets/derail_studs.jpg){: style="height:350px;width:350px"}
  
3. Place the slotted base of the solar panel assembly onto the threaded stud pattern on the side of the device that receives more sun
4. Adjust solar panel rotation to desired angle
5. Ensure the light is not casting a shadow on the solar panel
6. Thread washers and 1/4"-20 nuts onto base studs and tighten

![Derail Solar Panel](assets/solar_adjust.jpg){: style="height:350px;width:350px"}

7. Adjust solar panel tilt to desired angle and tighten bolts
8. Feed the wires through the cable glands into controller enclosure

![Derail Solar Panel Wire](assets/derail_charger_wire.jpg){: style="height:350px;width:350px"}

`` Do not connect battery wire until all installation steps are complete ``

9. Connect the wires to ``Solar Panel +`` and ``Solar Panel -`` terminals on the board as shown
10. Use a multimeter to test the connections

## 3.3 Sensor Installation

### For Flip-Style Derail

1. Locate bracket on side of derail
2. Move derailer side to side, to the nearest and furthest extent, making sure sensor is clear of moving parts
3. Ensure sensor will be clear of wheels
4. Grind paint off of mating face of sensor bracket before welding
5. Mount sensor to bracket with provided screws
6. Double check that sensor is clear, square to rail, and reader face is parallel to metal plate of derail
7. Weld sensor and bracket assembly to derail as shown

![Derail Sensor](assets/derail_sensor.jpg){: style="height:350px;width:350px"}

### For Swing-Style Derail

``Stand for swing-style derail sensor provided by Marmon``

1. Locate bracket on stand 
2. Bolt bracket to stand

### Liquid-Tight tubing

``Liquid tight tubing provided by Marmon``

1. Measure length of tubing from sensor to controller
2. Cut tubing to length, leaving a little extra in case of adjustment
3. Run cable through tubing from sensor to controller

![Sensor Bracket](assets/tubing_nut.jpg){: style="height:350px;width:350px"}

4. Slide the bracket straight down on to the sensor
5. Move bracket forward and back to adjust
7. Once positioned, tighten top bolts to secure bracket
8. Pass sensor wire through cable gland into controller housing

![Derail Solar Panel](assets/derail_sensor_wire.jpg){: style="height:350px;width:350px"}

8. Connect the sensor wires to ``IN 0`` on the board as shown
9. Use a multimeter to test the connections
10. Straighten tubing path
11. Bolt liquid-tight tubing cover plate perpedicular to rail as shown
12. Cover tubing with ballast

## 3.4 Turning on the System

![Derail Charger Connected](assets/solar_control.jpg){: style="height:350px;width:350px"}

Connect battery wire as shown. Look for light on charge controller and board to indicate sensor is receiving power.
If system does not turn on, contact TXRX for support.
