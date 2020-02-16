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

There are a few questions that should be answered before you begin your build.  To answer these questions it's best to start at the end and work backwards to define your requirements.  

But before you do, we recommend you skim the rest of the docs to get familar with the devFrame in general, and the structure of the docs specifically.  Have a look at some of the community builds to see some capabilities.  Then come back here and spend some time thinking about what you need to build to meet you goals.

The good news is the devFrame is designed to be very flexible and easy to change in size and configuration.  So if your first attempt does not meet your goals like you planned, you can iterate rather easily compared to most other frame options.

How do you plan to use your robot?  Remember, good design is the right set of compromises to get the job done.  Perfect design has a name --- it's called Art -- Leave that to the Artists while we go build stuff.  The following considerations are not a complete list, but should help you collect enough detail to start building.  Then iterate.

### Budget Requirements
- Do you already have stuff?  Reduce, reuse, recycle.
- Broke?  Smaller is usually cheaper.
- Going to use for business?  Align your goals and avoid bright shiny objects unless they meet said goals.

### Logistics Requirements
- Do you already have stuff?  Reduce, reuse, recycle.
- What kind of stuff can you get easily?  Some parts easier to source in some areas.
- How big can it be?  Max size, safety, regulations.
- Do you need to ship it?  Max size, battery size
- How will you ship or transport or store it?  Max size, case size, trunk/boot size
- How will you charge batteries?  Bigger batteries, bigger chargers.

### Data Requirements
- What type of data do you need?  Payload type and size.  Companion type and size.
- How do you plan to get the data? Logs, offboard, WiFi, analog.
- How often do you need the data?  Realtime or post process.  Frames per second for video.  Time lag for EKF integration.
- Do you need supplemental data?  Altitude, camera events, RTK GNSS.
- How accurate does the data need to be?  LIDAR vs GPS Altitude vs barometer, L1 vs L1/L2 RTK GNSS.

### Performance Requirements
- Do you need to fly indoors?  Max size, energy, prop protection.
- How long do you need to fly?  Max size, battery size, drive efficiency, one or multiple flights.
- Max endurance or max range?  Prop and/or battery selection, disk loading.
- Weather and wind?  Size, power, disk loading, drag, IP rating.

## Example Builds

We will post some examples builds and the thinking behind them here soon.





