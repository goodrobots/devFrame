---
title: "Flight Controller"
permalink: /docs/flight-controller/
---
Note -- An important factor in choosing a flight controller for your project is the number and types of ports supported by the board.  In particular, ensure that your flight controller has enough DShot capable motor outputs, as well as enough serial ports to support all sensor and telemetry connections. 
{: .notice--primary}

In this step we will install the flight controller with safety switch.  We have chosen to use the PixRacer for this build as we like the mix of size, capabilities and support.  Any ArduPilot compatible flight controller with right number and types of ports will work.  Just remember, the parameter file we will include in a later step will be specific to the PixRacer, so adapt as required.

![FC Switch Tools]({{ site.baseurl }}/assets/images/flight-controller/fc-switch-tools.jpeg){: width="80%" .align-center}

## What You Need (BOM)
The following should be everything you need to install the flight controller and safety switch.  

### Printed Parts

Qty | Part | Notes 
---|---|---
1 | Switch Mount Angle | Accessory Mounts >> Generic

### Flight Controller

Qty | Part | Notes 
---|---|---
1 | Pixracer | With case
1 | Safety Switch | With buzzer

### Fasteners

Qty | Part | Notes 
---|---|---
4 | M3 x 20 Machine Screw | PixRacer, Phillips or hex drive
2 | #4 x 3/8in Panhead Screw | TFMini mount, Phillips drive  

### Cables

Qty | Part | Notes 
---|---|---
1 | 6 Pins JST-GH to 6 Pins JST-GH | Power, current/voltage sense w/ buzzer

### Tools
- 2.5mm hex driver (if you use hex drive for flight control mounting)
- #1 Phillips screw driver
- Knife
- 3mm drill bit (if you need to make bigger mounting holes in your PixRacer case)
- Drill 

### Misc
- Double-sided Tape

## Step 1 - Mount Flight Controller

This step is pretty easy.  We are just going to attach the flight controller to PDB stack from last step and plug into PDB.  You will need:

- PixRacer w/ case
- 4 x M3 x 20mm screws
- Power Cable (6P JST-GH to 6P JST-GH) 

Note -- We modified the PixRacer case from mRo by drilling out the mouting holes with a 3mm drill bit.  This allows us to use M3 screws to attach through the case and into PDB stack.
{: .notice--primary}


