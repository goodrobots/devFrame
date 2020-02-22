---
title: "Frame Details"
permalink: /docs/frame-details/
---
![d450 Base Frame]({{ site.baseurl }}/assets/images/d450/d450-base-frame.jpeg){: .align-center width="80%"}

The devFrame is designed as a simple box truss using printed parts on each end to clamp four tubes running between the ends.  It provides a very strong structure with large internal volume, and minimal weight penalty when making the box longer. 

![Box End]({{site.baseurl}}/assets/images/devFrame-front-wide.jpeg){: width="80%" .align-center}

The carbon fiber tubes are 10mm diameter on the box frame and 10mm or 12mm for the arm tubes.  10mm arm tubes are recommended for smaller and lighter builds up to about 400mm wheelbase, while 12mm arm tubes can be used when building +400mm wheelbase frames.

## Interfaces
The devFrame has adopted a 15mm on center spacing for mounting accessories.  There are also some parts such as the cross mounts which provide a range of 7.5mm on center hole spacing.  The parts provide either through holes or pilot holes using this spacing.

![Cross Mounts]({{site.baseurl}}/assets/images/frame-details/cross-mount-x2.jpeg){: width="80%" .align-center} *Cross Mounts with pilot holes*
{: .text-center} 

In general, when you see an accessory mount for the devFrame it is typically adapting 15mm mounting hole spacing to whatever spacing is required to mount the accessory.

![Mount Examples]({{site.baseurl}}/assets/images/frame-details/mount-examples.jpeg){: width="80%" .align-center} *Mount assortment showing various through hole patterns*
{: .text-center}

The Arm Tube Clamps support mounting either perpindicular to the centerline, as in an H Frame, or at a 30deg angle for Stretch X.

![Arm Tube Clamp Top View]({{site.baseurl}}/assets/images/frame-details/arm-tube-clamp-top.jpeg){: width="80%" .align-center} *Top view of Arm Tube Clamp showing dual mounting options*
{: .text-center}

The 10mm box tubes are spaced 60mm on center laterally so they are compatible with off the shelf payload and battery mounts such as this [Tarot gimbal hook](https://www.amazon.com/dp/B00V7P3K9A/). 

## 3D Printed Parts
### Frame Parts
{% for part in site.data.printedParts %}

#### {{ part.name }} 

{% if part.imageName %}
  ![{{ part.name }}]({{site.baseurl}}/assets/images/frame-details/{{ part.imageName }}){: width="40%" .align-left}
{% endif -%}
{{ part.description }} 
{: .text-left}

{{ part.notes}}

[View and Download]({{ site.github.repository_url }}{{ site.stlurl }}{{ part.folder | uri_escape }}/{{part.fileName | uri_escape}})

{% endfor %}

### Arm Mounts

### Accesory Mounts


## Carbon Fiber Tubes
The devFrame requires the use of roll wrapped carbon fiber tubes.  They are not very cheap but they are very strong and light.  We are using metric tube sizes to help with international sourcing of tubes.
- 10mm carbon fiber tubes are used for the box frame, and arms for smaller builds [Amazon](https://www.amazon.com/dp/B015Z1RU6U/) or [eBay](https://www.ebay.com/itm/2pcs-10MM-OD-X-8MM-ID-X-500MM-100-Roll-Wrapped-Carbon-Fiber-Tube-3K-Glossy-US/133002010164)
- 12mm carbon fiber tubes are used for the arms of larger builds [Amazon](https://www.amazon.com/dp/B00TF8V05W/) or [eBay](https://www.ebay.com/itm/1-4pcs-12MM-OD-X-10MM-ID-X-500MM-100-Roll-Wrapped-Carbon-Fiber-Tube-3K-Tubing-/132362184137)

Each build will list the details of tube lengths and sizes used, but in general two 500mm lengths *each* of 10mm and 12mm should be enough to build a 450 class devFrame.

Note -- Tube sizes are given in outside diameter.  Wall thickness should be 1mm.  You may see tubes listed as 8mmx10mmx500mm, which means they have an 8mm inside diameter (ID), 10mm outside diameter (OD), and 500mm length.
{: .notice--primary}

Note -- Roll wrapped tubes are made by wrapping carbon fiber around a mandrel.  This results in tight tolerances for the ID (matching the mandrel size) but the OD may vary depending on manufacture.  The devFrame is designed to handle some tolerances but you need to check your tube diameters to ensure a good clamping fit. 
{: .notice--primary}

**Caution** -- Using pultruded carbon fiber tubes is not supported as the clamping force created by the clamps can cause failure of the tube, and the frame itself.
{: .notice--info}

![Roll Wrapped vs Pultruded Tubes]({{site.baseurl}}/assets/images/frame-details/roll-wrapped-vs-pultruded.jpeg){: width="80%" .align-center} A roll wrapped tube on left vs a pultruded tube on right.
{: .text-center}  

## Fasteners
