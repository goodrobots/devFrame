---
title: "Flight Controller"
permalink: /docs/flight-controller/
---
Note -- One of the factors in choosing a flight controller for your project is the number and type of ports supported by the board.  In particular, ensure that your flight controller has enough DShot capable motor outputs, as well as enough serial ports to support all sensor and telemetry connections. 
{: .notice--primary}

In this step we will install the flight controller with safety/arming switch.  We have chosen to use the PixRacer for this build as we like the mix of size, capabilities and support.  Any ArduPilot compatible flight controller will work.  Just remember the parameter file we will include in a later step will be specific to the PixRacer, so adapt as required.

![FC Switch Tools]({{ site.baseurl }}/assets/images/flight-controller/fc-switch-tools.jpeg){: width="80%" .align-center}

## What You Need (BOM)
The following should be everything you need to install the flight controller and safety/arming switch.  

### Printed Parts

Qty | Part | Notes 
---|---|---
1 | TFMini Angle Mount | 

### Flight Controller

Qty | Part | Notes 
---|---|---
1 | Pixracer | with case

### Fasteners

Qty | Part | Notes 
---|---|---
4 | M3 x 20 | PixRacer, Phillips or hex drive 