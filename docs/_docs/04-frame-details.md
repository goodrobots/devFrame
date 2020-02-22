---
title: "Frame Details"
permalink: /docs/frame-details/
---
The devFrame is designed as a simple box truss using printed parts on each end to clamp four tubes running between the ends.  It provides a very strong structure with large internal volume, and minimal weight penalty when making the box longer. 

![Box End]({{site.baseurl}}/assets/images/devFrame-front-wide.jpeg){: width="80%".align-center}

The carbon fiber tubes are 10mm diameter on the box frame and 10mm or 12mm for the arm tubes.  10mm arm tubes are recommended for smaller and lighter builds up to about 400mm wheelbase, while 12mm arm tubes can be used when building +400mm wheelbase frames or rovers.

## Interfaces
The devFrame has adopted a 15mm on center spacing for mounting accessories.  There are also some parts such as the cross mounts which provide 30mm on center hole spacing.

![image goes here]()

In general, when you see an accessory mount for the devFrame it is typically adapting 15mm mounting hole spacing to whatever spacing is required to mount the accessory.

![image goes here]()

The Arm Tube Clamps support mounting either perpindicular to the centerline, as in an H Frame, or at a 30deg angle for Stretch X.

![image goes here]()

## 3D Printed Parts
### Frame
{% for part in site.data.printedParts %}
#### {{ part.name }} 
{{ part.description }} 

{{ part.notes}}

[View and Download]({{ site.github.repository_url }}{{ site.stlurl }}{{ part.category | uri_escape }}/{{part.fileName | uri_escape}})

{% endfor %}

## Carbon Fiber Tubes
The devFrame requires the use of roll wrapped carbon fiber tubes.  They are not very cheap but they are very strong and light.  We are using metric tube sizes to help with international sourcing of tubes.
- 10mm carbon fiber tubes are used for the box frame, and arms for smaller builds [Buy here]
- 12mm carbon fiber tubes are used for the arms of larger builds [Buy here]

Each build will list the details of tube lengths and sizes used, but in general two 500mm lengths *each* of 10mm and 12mm should be enough to build a 450 class devFrame.

Note -- Tube sizes are given in outside diameter.  You may see tubes listed as 8mmx10mmx500mm, which means they have an 8mm inside diameter (ID), 10mm outside diameter (OD), and 500mm length.
{: .notice--primary}

Note -- Roll wrapped tubes are made by wrapping carbon fiber around a mandrel.  This results in tight tolerances for the ID (matching the mandrel size) but the OD may vary depending on manufacture.  The devFrame is designed to handle some tolerances but you need to check your tube diameters to ensure a good clamping fit. 
{: .notice--primary}

**Caution** -- Using pultruded carbon fiber tubes is not supported as the clamping force created by the clamps can cause failure of the tube, and the frame itself.
{: .notice--info}

![image here]()

## Fasteners
