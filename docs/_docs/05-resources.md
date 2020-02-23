---
title: "Resources"
permalink: /docs/resources/
---
This page contains links to resources that can help you complete and maintain a devFrame build.

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
- [APSync](https://ardupilot.org/dev/docs/apsync-intro.html) -- Primarly a serial to WiFi bridge for companion computer to MAVLink based autopilots.  It provides data sync along with video streaming services.

### Related Projects
- [Yaapu Telemetry](https://github.com/yaapu/FrskyTelemetryScript) -- An Open Source LUA script designed to run on OpenTX compatible transmitters such as FrSky and Jumper.  It provides MAVLink telemetry directly to your radio via the RC link.  
- [OpenTX](https://www.open-tx.org) Open Source firmware for FrSky and Jumper RC transmitters.

## Hardware
Like software, this is not an exhaustive list, but some of the more popular hardware in use.

### Autopilot Hardware
- [Pixhawk](https://pixhawk.org) -- Is an independent open hardware project.  It helps set the standard for the flight controllers in the open source community.
- [F4/F7/Linux](https://ardupilot.org/copter/docs/common-autopilots.html) -- ArduPilot now supports many different flight controllers.  Most of these come from the FPV community.  

### Companion Computers
- [Raspberry Pi](https://www.raspberrypi.org) -- The SBC that sets the standard for the Maker community with an easy to install OS and prime features that just work.  
- [Up Core](https://up-board.org/upcore/specifications/) -- More money than RPi but also more powerful.  Intel architecture can make it easier to find drivers, libraries etc.
- [NVIDIA Nano](https://developer.nvidia.com/embedded/jetson-nano-developer-kit) -- The Nano Developer Kit is becoming pretty popular for computer vision on a budget.

## Searching
Knowing how to use search is an important part of being a good internet citizen, and community member.  It is considered bad form to ask a question in a support forum that has been previously asked, and likely already answered.  It is expected that you have done some searching to find your own answers prior to posting.

## Soldering
Owning or having access to quality soldering tools is a must for building your own robot.  Knowing how to use them correctly is just as important as owning them. [Here's a really good tutorial](https://www.makerspaces.com/how-to-solder/).  And plenty of videos on the web.  Do not underestimate the importance of helping hands and/or jigs to hold things in place while you solder.

Note -- We have some example kit for soldering and crimping over on our [Required Tools page]({{ site.baseurl }}/docs/tools/#solder-and-crimp).
{: .notice--primary}

## Crimping
Crimping pins is not a requirement, but can be a very handy skill to have.  Perhaps the most ubiquitous crimp pin is the Dupont style servo pin.  Here is a fascinating and detailed guide to [getting your crimps right](https://www.instructables.com/id/Make-a-Good-Dupont-Pin-Crimp-EVERY-TIME/).

## Cables And Connectors
Hopefully you got a bag of cables with your flight controller.  But sometimes you need more.  If you are using a flight controller that adheres to the Pixhawk Connector (formerly DroneCode Connector) Standard you need [cables](https://store.mrobotics.io/category-s/110.htm) with [JST-GH ends](https://www.amazon.com/dp/B07PLPT2Z6/).  If you are using an older flight controller it may have [DF13](https://store.mrobotics.io/category-s/116.htm) connectors.  

## Where To Buy Electronics
We understand that many builders will be on a tight budget.  However, it is very easy to confuse value with price.  They are not the same.  Forums are filled with stories of cheap clones not working like they should.  Do your homework and spend wisely.

Here is a list of vendors who specialize in small robotics and associated parts.  We are not affiliated with any of these vendors.  This is simply a list of vendors we have purchased from in the past, and think they offer fair value with consistent support.  If you do not see your favorite vendor on the list let us know and we can see about adding them.

- [Blue Robotics](https://bluerobotics.com) -- Mostly ArduSub and ROV stuff, but still cool.  And who's to say the devFrame can't support a sub.
- [Dimension Engineering](https://www.dimensionengineering.com) -- Good selection of power electronics such as motor drivers and regulators.
- [GetFPV](https://www.getfpv.com) -- Good source for smaller motors, speed controls, and flight controllers.  They also carry PixHawk branded stuff.
- [IR-Lock](https://irlock.com) -- An ArduPilot Partner with PixHawk, IR Lock and other sensors.
- [Myan Robotics (mRo)](https://mrobotics.io) -- One of the only US manufacturers of flight controllers and sensors for the DIY and custom markets.  Founded by Jordi Munoz, co-founder of 3D Robotics back when...well, that's another story.  
- [Pololu](https://www.pololu.com) -- Robot kits and parts.  Big selection and they have added a custom laser cutting service, which is cool.
- [RobotShop](https://www.robotshop.com/en/) -- All kinds of robot related parts.
- [Servo City](https://www.servocity.com) -- Not just servos.  Robot kits and parts, plus some cool mounts and motion options.
- [SparkFun](https://www.sparkfun.com) -- Board level components, breakout boards, and DIY electronic kits.  Plus some really nice learning resources.
