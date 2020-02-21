---
title: "Start At The End"
permalink: /docs/start/
---

There are a few questions that should be answered before you begin your build.  To answer these questions it's best to start at the end and work backwards to define your requirements.  

But before you do, we recommend you skim the rest of the docs to get familiar with the devFrame in general, and the structure of the docs specifically.  Have a look at some of the community builds to see some capabilities.  Then come back here and spend some time thinking about what you need to build to meet you goals.

How do you plan to use your robot?
{: .notice--primary}

Remember, good design is the right set of compromises to get the job done.  Perfect design has a name -- it's called Art -- leave that to the Artists while we go build stuff.  The following considerations are not a complete list, but should help you collect enough detail to start building.  Then iterate.

## Budget Requirements
- Do you already have stuff?  Reduce, reuse, recycle.
- Limited Budget?  Join the club.  Smaller is usually cheaper.  Expect to have at least $30 US in the frame; most of that is carbon fiber tube; the rest depends on how you source the printed parts.
- Going to use for...?  Align your goals and avoid bright shiny objects unless they meet said goals.

## Logistics Requirements
- Do you already have stuff?  Reduce, reuse, recycle.
- What kind of stuff can you get easily?  Some parts easier to source in some areas.
- How will you ship or transport or store it?  Max size, case size, trunk/boot size

## Data Requirements
- What type of data do you need?  Payload type and size.  Companion type and size.
- How do you plan to get the data? Logs, offboard, WiFi, analog.
- How fast/often do you need the data?  Realtime or post process.  Frames per second for video.  Time lag for EKF integration.
- Do you need supplemental data?  Altitude, camera events, RTK GNSS.
- How accurate does the data need to be?  LIDAR vs GPS Altitude vs barometer, L1 vs L1/L2 RTK GNSS.

## Communication Requirements
- What protocols and/or API's to use?  MAVLink, ROS/DDS, WiFi 802.11a/b/g/n/ac.  
- What frequency(s) to use?  RC 900/2.4, WiFi 2.4/5.8, Analog 433/866/900.  Interference,  regulations, range, bandwidth.
- Do you have enough serial ports for all sensors, companions, comms?  More ports on some FC's than others.  

## Operational Requirements
- Do you need to fly indoors?  Max size, energy, prop protection.
- How big can it be?  Max size, safety, regulations.
- How long do you need to fly?  Max size, battery size, drive efficiency, one or multiple flights.
- Max endurance or max range?  Prop and/or battery selection, disk loading.
- Weather and wind?  Size, power, disk loading, drag, IP rating.

## Examples
Have a look at the Community Builds section to see some capabilites and limitations in action.


