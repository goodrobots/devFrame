---
title: "Receiver, GPS, and Sensors"
permalink: /docs/receiver-gps-sensors/
---

Note -- An important factor in choosing a flight controller for your project is the number and types of ports supported by the board.  In particular, ensure that your flight controller has enough serial ports to support all sensor and telemetry connections. 
{: .notice--primary}

In this step we will install the RC receiver, GPS module and LiDAR sensor.  We have chosen our sensors for this build based on a mix of size, capabilities and support.  Any ArduPilot compatible GPS/compass module will work.  You also need to choose a receiver for your particular brand of radio.  We really like FrSky for it's pass-through telemetry support in ArduPilot.  The TFMini LiDAR is optional, but we like the better precision it offers in flight modes that can leverage the data.  Just remember, the parameter file we will include in a later step will be specific to these sensors, so adapt as required.

![GPS Sensor Tools]({{ site.baseurl }}/assets/images/gps-sensors/gps-sensors-tools.jpeg){: width="80%" .align-center}

**Caution** -- This section requires soldering.  A bad solder joint can cause complete loss of power so please make sure you are comfortable creating good solder joints before proceeding.
{: .notice--info}

## What You Need (BOM)
The following should be everything you need to install the Receiver, GPS and TFMini LiDAR.

### Printed Parts

Qty | Part | Notes 
---|---|---
1 | Cross Mount | Receiver
1 | mRo GPS Mount | Per choice of GPS 
1 | mRo GPS Cover | Optional 
1 | Benewake TFMini Mount Angle |  

### Electronics

Qty | Part | Notes 
---|---|---
1 | mRo M8N GPS | w/ compass
1 | FrSky X8R Receiver | w/ PCB antennas
1 | Benewake TFMini LiDAR | Serial

### Cables

Qty | Part | Notes 
---|---|---
1 | 6 Pins JST-GH to 6 Pins JST-GH | GPS
1 | 6 Pins JST-GH to 4 Pins JST-GH | TFMini, Custom soldered for serial connection
1 | 3 Pin Servo (SPort) to 4 Pin JST-GH  | FrSky Telemetry
1 | 3 Pin Servo (SBus) to  5 Pin JST-GH | RC In

### Fasteners

Qty | Part | Notes 
---|---|---
2 | #4 x 3/8in Pan Head Screw | TFMini mount, Phillips drive 
2 | M3 x 12mm Pan Head Screw, Nylon | GPS mount
4 | M2 x 20mm Pan Head Screw, Nylon | GPS cover
4 | M2 Nut, Nylon | GPS Cover
2 | M3 Nut, Nylon | GPS Mount Standoffs

### Standoffs

Qty | Part | Notes 
---|---|---
2 | M3 x 20mm, Male-Female, Nylon | GPS mounting 

### Tools

- #1 Phillips screw driver
- Knife
- 3mm drill bit 
- Drill 

### Misc

- Double-sided Tape
- Velcro (sticky back)
- (2) Zip Ties
- (2) 1/4in x ~1in Heat Shrink Tube
- [PixRacer Pinout](https://ardupilot.org/copter/docs/common-pixracer-overview.html#connector-pin-assignments)

**Caution** -- Before proceeding please make sure you are familiar with your flight controller and sensor port pinouts.  Incorrect wiring can cause systems failures and damage to hardware.  
{: .notice--info}

