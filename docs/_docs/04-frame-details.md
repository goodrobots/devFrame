---
title: "Frame Details"
permalink: /docs/frame-details/
---
## Design
![image-left]({{site.baseurl}}/assets/images/devFrame-front-wide.jpeg){: .align-left}

The devFrame is designed as a simple box truss using printed parts on each end to clamp four tubes running between the ends.  It provides a very strong structure with large internal volume, and minimal weight penalty when making the box longer. 

The carbon fiber tubes are 10mm diameter on the box frame and 10mm or 12mm for the arm tubes, depending on the size of the frame being built.  10mm arm tubes are recommended for smaller and lighter builds up to about 400mm wheelbase, while 12mm arm tubes can be used when building +400mm wheelbase frames or rovers.

## Interfaces
The devFrame has adopted a 15mm on center spacing for mounting accessories.  There are also some parts such as the cross mounts which provide 30mm on center hole spacing.  The 10mm frame tubes are 60mm on center to support off the shelf mounts and hardware such as small gimbal hangars and battery trays.

In general, when you see an accessory mount for the devFrame it is typically adapting 15mm mounting hole spacing to whatever spacing is required to mount the accessory.

The Arm Tube Clamps support mounting either perpindicular to the centerline, as in an H Frame, or at a 30deg angle for Stretch X.

## 3D Printed Parts
### Frame
{% for part in site.data.printedParts %}
#### {{ part.name }} 
{{ part.description }} 

{{ part.notes}}

[View and Download]({{ site.github.repository_url }}{{ site.stlurl }}{{ part.category | uri_escape }}/{{part.fileName | uri_escape}})

{% endfor %}

## Carbon Fiber Tubes

## Fasteners
