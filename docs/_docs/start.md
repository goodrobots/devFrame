---
title: "Start At The End"
permalink: /docs/start/
toc: true
---

## The devFrame Is For...

Short answer:  Anyone who wants to build a small quad copter or rover.

Long answer:  Robot builders and developers who need or want the flexibility of building robots from open source ecosystems while removing costs of one-off custom frames, or lock-in associated with a proprietary frame.

### Some Assumptions
While we try to provide enough information to help you achieve your devFrame building goals we do make some assumptions about skill and motivation levels.  Building a robot from a kit is time consuming.  The biggest goal for the devFrame project is to reduce the amount of time and effort involved to build, but it still takes a commitment to read and learn the required information.  

We assume that you are familiar with open source flight stacks such as ArduPilot or PX4.  We also assume that you know how to use basic tools such as screw drivers, and that you know how to solder.  Or know someone who does.  If you do not have skills with tools or a soldering iron we have provided some resources here, as it's never too late to learn.

Overall, if we do not have the answer we will try to point you in the right direction to go find it.  If you feel like we missed something let us know.  And remember, *search is your friend*.


## Define Basic Requirements

There are a few questions that should be answered before you begin your build.  To asnwer these questions it's best to start at the end and work backwards to define your requirements.

But before you do, we recommend you skim the rest of the docs to get familar with the devFrame in general, and the structure of the docs specifically.  Have a look at some of the community builds to see some capabilities.  Then come back here and spend some time thinking about what you need to build to meet you goals.

The good news is the devFrame is designed to be very flexible and easy to change in size and configuration.  So if your first attempt does not meet your goals like you planned, you can iterate rather easily compared to most other frame options.

How do you plan to use your robot?  The following questions are not a complete list, but should help you answer that question with enough detail to start building.

### Data Requirements

- What type of data do you need?  This drives payload and sensors.  For example, if you are doing Computer Vision devlopment you might need a camera that provides video at a high enough frame rate to 
- How are you going to get the data you need?
- Or maybe you are just flying for fun so just need a bit of telemetry to keep an eye on things.  What type and size of sensor(s) do you need to fly to gather your data?
-  Basic telemetry can come from FrSky Telemetry support and is good enough for basic use.  Without the need for extra equipment beyond the proper cable and an open serial port it represents a good value for most builds.   But it will not help you pass MavLink Telemtry to a GCS or offboard computer.  We like it so much we plan on using it on every build.
-  If you are developing for computer v   

### Performance Requirements

Do you need to fly indoors.





