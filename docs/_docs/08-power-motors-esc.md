---
title: "Power, Motors, ESC's"
permalink: /docs/power-motors-escs/
---

**Caution** -- This section requires soldering.  A bad solder joint can cause complete loss of power so please make sure you are comfortable creating good solder joints before proceeding.
{: .notice--info}

In this section we will install power distribution, motors, and electronic speed controls (ESC's). 

## Power Planning

Note -- One of the more challenging aspects of building your own robot is providing clean power to various components.  Make sure you consider all current and future power requirements for your use case.
{: .notice--primary}

There are many different types and brands of equipment that can meet your onboard and flight power needs.  We are using what we had available in the shop, as well as what we feel represents a general 450 class setup.  

### Power Distro

In this guide we will use an ACP4 Power Distribution Board (PDB) that includes current and voltage sense, as well as both 5V and 12V voltage regulators (BEC).  We will use the 5V BEC to power the flight controller (PixRacer), and add an additional Castle 5V BEC to power the companion computer and sensors.  Any similar PDB will do fine, but we do recommend you have a seperate 5V source for your flight control and companion computer.  

### Motors

We have chosen T-Motor Air Gear 350 set, which includes four AIR2213 KV920 brushless motors, and four plastic T9545 self-tighhtening props.  Partly because we already had a set, and also because they are a good value.  At the time of this writing the Air Gear 350 can be hard to find.  Some sets include the ECS's, but for this build we are using ESC telemetry so went with another brand.  Any motors in the 900-1000kV range with 8-10in props should work fine.

### ESC's

For ESC's we are using four Luminier BLHeli32 36A with ESC telemetry support.  Any ESC with proper power handling will work just fine, but we do highly recommend DShot and ESC telemetry support as it will make tuning much easier.

### Battery

Although we will not need the battery in this section we are planning on using a 4S 4350mAHr lipo.  You could use a 3 or 4 cell setup for a 450.  Again we are using what we had in the shop, so 4S it is.

Note -- Keep in mind that the recommended max gross weight for the devFrame is 2kg or 4.4 pounds.  Running a larger battery may mean you are payload limited.  Running a larger payload may mean you are battery, and therefore flight time limited.  
{: .notice--primary}


## What You Need (BOM)
The following should be everything you need to install power distribution, motors and ESC's.

### Printed Parts

Qty | Part | Notes 
---|---|---
8 | Motor Mount Half 12mm | 
6 | Cross Mount | 
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
1 | MRo ACSP4 Power Distro Board (PDB) w/ BECs  |  Or equivalent 
1 | Castle 5V BEC | Or equivalent
1 | 12 AWG Silicone Hookup Wire | Battery to PDB


### Misc
- Small zipties
- Double sided tape

### Tools
- #1 and #2 Phillips screwdriver
- 