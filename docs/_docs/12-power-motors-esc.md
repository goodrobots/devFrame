---
title: "Power, Motors, ESC's"
permalink: /docs/power-motors-escs/
---

**Caution** -- This section requires soldering.  A bad solder joint can cause complete loss of power so please make sure you are comfortable creating good solder joints before proceeding.
{: .notice--info}

In this section we will install power distribution, motors, and electronic speed controls (ESC's). 

[power system image]

## Power Planning

Note -- One of the more challenging aspects of building your own robot is providing clean power to various components with different voltage and current demands.  Make sure you consider all power requirements for your use case.
{: .notice--primary}

There are many different types and brands of equipment that can meet your onboard and flight power needs.  We are using what we had available in the shop, as well as what we feel represents a general 450 class setup.  

### Power Distro

In this guide we will use an ACP4 Power Module, which will also act as our Power Distribution Board (PDB).  The ACP4 includes current and voltage sense, as well as both 5V and 12V voltage regulators (BEC).  We will use the 5V BEC to power the flight controller (PixRacer in this build) and sensors.  We will add an additional Castle Creations 10A BEC set to 5V output to power the optional companion computer (RPi 4 in this build).  Any similar power module and/or PDB will do fine, but we do recommend you have a seperate 5V source for your flight control and companion computer.  

### Motors

We have chosen a T-Motor Air Gear 350 set, which includes four AIR2213 KV920 brushless motors, and four plastic T9545 self-tighhtening props.  Partly because we already had a set, and also because they are a good value.  At the time of this writing the Air Gear 350 can be hard to find.  Some Air Gear sets include the ECS's, but for this build we are using ESC telemetry so went with another brand.  Any motors in the ~900-1000kV range with 8-10in props should work fine for a 450 class build.

### ESC's

For ESC's we are using four Luminier BLHeli32 36A with DShot and ESC telemetry support.  Any ESC with proper power handling will work just fine, but we do highly recommend DShot and ESC telemetry support as it will make tuning much easier.  4-in-1 ESC's are also an option, and do provide a cleaner build in terms of wiring harness.

### Wire and Connectors

We prefer stranded silicone wire for power (and signal) distribution.  It is flexible and works well in high vibration environments.  For this build we are using 14AWG for the battery connection.  Motors and ESC's are equiped with 16 or 18 AWG from the factory.  See Resources section for more info on wire gauge (AWG) etc. 

In our shop we use 45A Anderson Power Poles for connectors on builds 450 or larger.  We prefer the crimp connections.  We use XT series connectors for smaller builds, which is a more popular option in the RC community.  For a 450 build an XT60 will work well.  See the Resources page for more info on connectors.

### Battery

Although we will not need the battery in this section we are planning on using a 4S 4350mAHr lipo.  You could use a 3 or 4 cell setup for a 450.  Again we are using what we had in the shop, so 4S lipo it is.  See Resources page for more info on battery details and nomenclature.

Note -- Keep in mind that the recommended max gross weight for the devFrame is 2kg or 4.4 pounds.  Running a larger battery may mean you are payload limited.  Running a larger payload may mean you are battery, and therefore flight time limited.  
{: .notice--primary}


## What You Need (BOM)
The following should be everything you need to install power distribution, motors and ESC's.

### Printed Parts

Qty | Part | Notes 
---|---|---
8 | Motor Mount Half 12mm | 
4 | Cross Mount | 
1 | mRo GPS Mount | Per choice of GPS 
1 | mro GPS Cover | Optional 
1 | Benewake TFMini Mount | Optional 

### Machine Screws 

Qty | Size | Note
--- | --- | ---
8 | M3 x 22mm  |  Motor Mounts

### Standoffs

Qty | Size | Note
--- | --- | ---
4 | M3 x 6mm  |  Vibration Isolation 
4 | M3 Hex Nut | 

### Power Distribution

Qty | Size | Note
--- | --- | ---
1 | MRo ACSP4 Power Module |  Or equivalent 
1 | Castle Creations 10A BEC | Or equivalent


### Wire and Connectors

Qty | Size | Note
--- | --- | ---
1ft | 14 AWG Silicone Wire | Battery to PDB
1ft | 16 AWG Silicone Wire | Optional - depends on motors and ESC's 
2 pair | Anderson Power Poles 45A | XT60 or equivalent 

### Misc
- Small zipties
- Double sided tape
- Heat Shrink Tube
- (2) 0.1in Single Row Header Pins - Optional; depends on ESC telemetry connection

### Tools
- #1 and #2 Phillips screwdriver
- Needle Nose Pliers
- Wire Cutters
- Wire Strippers
- Soldering Kit

## Step 1 - Flight Power Wiring

Note -- The motor mounts are deigned to support routing the wires inside the arm tube.  In this build we will route outside the tube.  It is largely a matter of preference, but routing motor wires outside the arm tube is slightly easier to assemble and maintain.
{: .notice--primary}

In this step we will connect wires betweem motors and ESC's, as well as between ESC's and PDB.

### 1.1 - Motors to ESC's
- To get accurate distance locate mounting position for the ESC's. We will install our ESC's for this build on the Arm Tube clamps using double-sided tape and zipties.  



- Measure and note distance between motors and ESC's.  Add a few millimeters to allow for overlappig solder joints.
- Solder each motor wire to ESC wire.
- Repeat three more times until all motor to ESC wires are soldered   


### 

[image here]

### 


