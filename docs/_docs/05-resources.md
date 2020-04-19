---
title: "Resources"
permalink: /docs/resources/
---
This page contains links to resources that can help you complete and maintain a devFrame build.

## Frame Sizes and Geometry
In these docs we talk about frames such as "450 class stretch X", and other letters of the alphabet when referencing frames.  It's not as bad as it sounds once you see a few drawings and examples.  450 is 450mm from motor center to motor center on the diagonal, and stretch X means it's shaped like an X with the center portion stretched a bit along the forward flight axis.  Rather than reinvent the wheel here are a few good posts on the subject:
- [Drone Frame Styles](https://www.getfpv.com/learn/new-to-fpv/all-about-multirotor-fpv-drone-frame/) -- From GetFPV so focused on...FPV.
- [Drone Frame to Battery Size](https://www.genstattu.com/blog/how-to-choose-quadcopter-frame/) -- From GensTattu, a battery maker, so focused on frame and battery size comparisons.

## Software
This list contains only your free and Open Source options.  There are other options, but these are the main projects we feel are a good match for use with devFrame.  

Note -- We only provide support for Goodrobot projects.  We highly recommend joining the forums and support channels for the projects you use.
{: .notice--primary}

### Autopilot Firmware
- [ArduPilot](https://ardupilot.org) -- An independent Open Source project licensed under GPLv3.  ArduPilot is very flexible and supports a variety of robot types and configurations.  Our initial documentation will cover ArduPilot, but we do have plans to better support PX4.  
- [PX4](https://px4.io) -- Open Source flight control software licensed under BSD 3-Clause.  Part of Dronecode and Linux Foundation.

Note -- There can be big differences in Open Source licenses.  If you think it matters, make sure you do your homework.  If it really matters you likely need a lawyer.
{: .notice--primary}

### Ground Control Software (GCS)
- [Maverick Web](https://github.com/goodrobots/maverick-web) -- A sister project from Goodrobots.  Still in early development.  When it's done it will be a web based GCS.
- [Mission Planner](https://ardupilot.org/planner/) -- The GCS for ArduPilot geeks.  Windows only.  The interface can be a bit overwhelming at times as it has many advanced features.  We use it a bunch as it is well documented for use with the main ArduPilot features.
- [QGroundControl(QGCS)](http://qgroundcontrol.com) -- GCS for anything that talks MAVLink.  From the same people who brought you PX4.  Also part of Dronecode and Linux Foundation.
- [MAVProxy](https://ardupilot.github.io/MAVProxy/html/index.html) -- A light-weight command-line based GCS with modules available to add functionality.  

### Companion Computer Images 
- [Maverick](https://github.com/goodrobots/maverick) -- The original Goodrobots project.  Maverick is in the process of being updated and will be the go to solution for getting companion computers doing cool things on robots.
- [APSync](https://ardupilot.org/dev/docs/apsync-intro.html) -- Primarily a serial to WiFi bridge for companion computer to MAVLink based autopilots.  It provides data sync along with video streaming services.

### Related Projects
- [OpenTX](https://www.open-tx.org) Open Source firmware for FrSky and Jumper RC transmitters.
- [Yaapu Telemetry](https://github.com/yaapu/FrskyTelemetryScript) -- An Open Source LUA script designed to run on OpenTX compatible transmitters such as FrSky and Jumper.  It provides telemetry directly to your radio via the RC link.  

## Hardware
Like software, this is not an exhaustive list, but some of the more popular hardware in use.

### Autopilot Hardware
- [Pixhawk](https://pixhawk.org) -- Is an independent open hardware project.  It helps set the standard for the flight controllers in the open source community.
- [F4/F7/Linux](https://ardupilot.org/copter/docs/common-autopilots.html) -- ArduPilot now supports many different flight controllers.  Most of these come from the FPV community.  

### Companion Computers
- [Raspberry Pi](https://www.raspberrypi.org) -- The SBC that sets the standard for the Maker community with an easy to install OS and prime features that just work.  
- [Up Core](https://up-board.org/upcore/specifications/) -- More money than RPi but also more powerful.  Intel architecture can make it easier to find drivers, libraries etc.
- [NVIDIA Nano](https://developer.nvidia.com/embedded/jetson-nano-developer-kit) -- The Nano Developer Kit is becoming pretty popular for computer vision on a budget.

### Wire Gauge
We will use AWG - short for American Wire Gauge - in these docs.  The system and nomenclature is confusing as the bigger the gauge, the smaller the cross section of conductor.  Things can also get a bit more confusing for our short length, high DC power needs as AWG ampacity charts are typically for use in larger systems such as wiring a building.  For typical use in the devFrame we should be able to use 12-14AWG for battery connections and 16-18AWG connections between speed controls and motors.  [See this Wikipedia article](https://en.wikipedia.org/wiki/American_wire_gauge) for all you wanted to know about AWG.      

### Signal Cables and Connectors
Hopefully you got a bag of cables with your flight controller.  But sometimes you need more.  If you are using a flight controller that adheres to the Pixhawk Connector (formerly DroneCode Connector) Standard you need [cables](https://store.mrobotics.io/category-s/110.htm) with [JST-GH ends](https://www.amazon.com/dp/B07PLPT2Z6/).  If you are using an older flight controller it may have [DF13](https://store.mrobotics.io/category-s/116.htm) connectors.

### Power Cables and Connectors 
We prefer stranded wire with silicone jacket for robot builds since it is highly flexible and designed for use in high vibration environments.  It's known as [silicone wire](https://www.amazon.com/12-Gauge-Silicone-Wire-Feet/dp/B0070RZXLW).

There are several options for power connectors in the robotics community.  The connector we prefer in this shop for larger builds is [Anderson Powerpoles](https://powerwerx.com/anderson-power-powerpole-sb-connectors) 45A.  They are not the cheapest connector, and do require spcial crimping tools, but we feel the crimp connections are superior to soldered.  Some builders do not like to use them as the 45A rating seems too low.  However, that rating has to do with the ampacity of the maximum supported wire size of the connector, which is 10AWG.  We have no problems using them in 100A robotics systems.  

Perhaps the most popular soldered power connection in the drone community is the XT series.  XT connectors are available in XT30, XT60 and XT90 sizes.  [This is a good blog post](https://blog.ampow.com/rc-battery-connector-types/) on different styles of connectors.    

### Fasteners Etc
The fasteners used for the base devFrame can all be sourced from a local hardware store.  However, there are always specialty bits that come in handy to keep a build going.  A good example is nylon and rubber standoffs for mounting power distribution, flight controllers and similar electronics.  Below is an example of some of the parts we have found handy to keep on hand:

- [M3 Anti-Vibration Standoffs](https://www.getfpv.com/anti-vibration-flight-controller-standoff-7mm.html) or [here](https://www.amazon.com/Controller-Anti-Vibration-Mounting-Hardware-Standoffs/dp/B06ZXT21DX)
- [M3 Nylon Standoffs](https://www.amazon.com/Litorange-Standoff-Threaded-Motherboard-Assortment/dp/B07D7828LC)
- [Tiny Screws](https://www.amazon.com/dp/B078W7XQ5S)

### Carbon Fiber Tube
The devFrame requires the use of roll wrapped carbon fiber tubes with 10mm and/or 12mm diameter. 

Note -- Tube sizes are given in outside diameter.  Wall thickness should be 1mm.  You may see tubes listed as 8mmx10mmx500mm, which means they have an 8mm inside diameter (ID), 10mm outside diameter (OD), and 500mm length.
{: .notice--primary}

- 10mm carbon fiber tubes are used for the box frame, and arms for smaller builds [Amazon](https://www.amazon.com/dp/B015Z1RU6U/) or [eBay](https://www.ebay.com/itm/2pcs-10MM-OD-X-8MM-ID-X-500MM-100-Roll-Wrapped-Carbon-Fiber-Tube-3K-Glossy-US/133002010164)
- 12mm carbon fiber tubes are used for the arms of larger builds [Amazon](https://www.amazon.com/dp/B00TF8V05W/) or [eBay](https://www.ebay.com/itm/1-4pcs-12MM-OD-X-10MM-ID-X-500MM-100-Roll-Wrapped-Carbon-Fiber-Tube-3K-Tubing-/132362184137)

Note -- Roll wrapped tubes are made by wrapping carbon fiber around a mandrel.  This results in tight tolerances for the ID (matching the mandrel size) but the OD may vary depending on manufacture.  The devFrame is designed to handle some tolerances but you need to check your tube diameters to ensure a good clamping fit. 
{: .notice--primary}

**Caution** -- Using pultruded carbon fiber tubes is not supported as the clamping force created by the clamps can cause failure of the tube, and the frame itself.
{: .notice--info}

![Roll Wrapped vs Pultruded Tubes]({{site.baseurl}}/assets/images/frame-details/roll-wrapped-vs-pultruded.jpeg){: width="80%" .align-center} A roll wrapped tube on left vs a pultruded tube on right.
{: .text-center}  

## Soldering
Owning or having access to quality soldering tools is a must for building your own robot.  Knowing how to use them correctly is just as important as owning them. [Here's a really good tutorial](https://www.makerspaces.com/how-to-solder/).  And plenty of videos on the web.  Do not underestimate the importance of helping hands and/or jigs to hold things in place while you solder.

Note -- We have some example kit for soldering and crimping over on our [Required Tools page]({{ site.baseurl }}/docs/tools/#solder-and-crimp).
{: .notice--primary}

## Crimping
Crimping pins is not a requirement, but can be a very handy skill to have.  Perhaps the most ubiquitous crimp pin is the Dupont style servo pin.  Here is a fascinating and detailed guide to [getting your crimps right](https://www.instructables.com/id/Make-a-Good-Dupont-Pin-Crimp-EVERY-TIME/).

## Calculators and Other Stuff
We use a lot of heuristics (fancy word for rules of thumb) around this shop.  You certainly will not find any calculus in the docs here.  Part of the benefit of building small open systems is it's often a better value just to build and test empirically.    But sometimes it's good to do some math.  Here are a few we planning tools that could be useful to support build planning:

- [Multicopter AUW and Motor Selection](https://www.flitetest.com/articles/choosing-multicopter-motors) -- Simple but nice spreadsheet to get you in the neighborhood.
- [eCalc](https://www.ecalc.ch/xcoptercalc.php) -- Free for limited use.  We see enough forum posts to indicate that it gets used.

## Searching
[Knowing how to use search](https://support.google.com/websearch/answer/2466433) is an important part of being a good internet citizen, and community member.  It is considered bad form to ask a question in a support forum that has been previously asked, and likely already answered.  It is expected that you have done some searching to find your own answers prior to posting.


## Where To Buy Stuff
We understand that many builders will be on a tight budget.  However, it is very easy to confuse value with price.  They are not the same.  Forums are filled with stories of cheap clones not working like they should.  Do your homework and spend wisely.

Here is a list of vendors who specialize in small robotics and associated parts.  We are not affiliated with any of these vendors.  This is simply a list of vendors we have purchased from in the past, and think they offer fair value with consistent support.  If you do not see your favorite vendor on the list let us know and we can see about adding them.

- [Blue Robotics](https://bluerobotics.com) -- Mostly ArduSub and ROV stuff, but still cool.  And who's to say the devFrame can't support a sub.
- [Dimension Engineering](https://www.dimensionengineering.com) -- Good selection of power electronics such as motor drivers and regulators.
- [GetFPV](https://www.getfpv.com) -- Good source for smaller motors, speed controls, and flight controllers.  They also carry PixHawk branded stuff.
- [IR-Lock](https://irlock.com) -- An ArduPilot Partner with PixHawk, IR Lock and other sensors.
- [KDE Direct](https://www.kdedirect.com/) -- High quality brushless motors and ESC's.
- [Myan Robotics (mRo)](https://mrobotics.io) -- One of the only US manufacturers of flight controllers and sensors for the DIY and custom markets.  Founded by Jordi Munoz, co-founder of 3D Robotics back when...well, that's another story.  
- [Pololu](https://www.pololu.com) -- Robot kits and parts.  Big selection and they have added a custom laser cutting service, which is cool.
- [RobotShop](https://www.robotshop.com/en/) -- All kinds of robot related parts.
- [Servo City](https://www.servocity.com) -- Not just servos.  Robot kits and parts, plus some cool mounts and motion options.
- [SparkFun](https://www.sparkfun.com) -- Board level components, breakout boards, and DIY electronic kits.  Plus some really nice learning resources.
