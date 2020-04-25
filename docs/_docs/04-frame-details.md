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

In general, when you see an accessory mount for the devFrame, it is typically adapting 15mm mounting hole spacing to whatever spacing is required to mount the accessory.

![Mount Examples]({{site.baseurl}}/assets/images/frame-details/mount-examples.jpeg){: width="80%" .align-center} *Mount assortment showing various through hole patterns*
{: .text-center}

The Arm Tube Clamps support mounting either perpindicular to the centerline, as in an H Frame, or at a 30deg angle for Stretch X.

![Arm Tube Clamp Top View]({{site.baseurl}}/assets/images/frame-details/arm-tube-clamp-top.jpeg){: width="80%" .align-center} *Top view of Arm Tube Clamp showing dual mounting options*
{: .text-center}

The 10mm box tubes are spaced 60mm on center laterally so they are compatible with off the shelf payload and battery mounts such as this [Tarot gimbal hook](https://www.amazon.com/dp/B00V7P3K9A/). 

## 3D Printed Parts
The following is a detailed list of currently available printed parts with build notes and print settings.

### Frame 
{% for part in site.data.printedParts %}

{% if part.folder == "Frame" and part.subFolder == undefined %}

#### {{ part.name }}

{% if part.imageName %}
![{{ part.name }}]({{site.baseurl}}/assets/images/frame-details/{{ part.imageName }}){: width="40%" .align-left}
{% endif -%}

[3D View and Download]({{ site.github.repository_url }}{{ site.stlurl }}{{ part.folder | uri_escape }}/{{part.fileName | uri_escape}}){: .btn .btn--inverse}
{: .text-center}

*Description:*  {{ part.description }} 

*Notes:*  {{ part.notes }}

*Print Profile:*  [{{ part.print}}]({{ site.baseurl }}/docs/printing/#print-settings)

---
{:style="clear: left"} 

{% endif %}

{% endfor %}

### Arm Mounts
The mounts you use for the arms depend on the size of arm tube you select.  10mm and 12mm arm tubes are currently supported.

{% for part in site.data.printedParts %}

{% if part.subFolder == "10mm Arm Tube" or part.subFolder == "12mm Arm Tube" %}

#### {{ part.name }} 

{% if part.imageName %}
![{{ part.name }}]({{site.baseurl}}/assets/images/frame-details/{{ part.imageName }}){: width="40%" .align-left}
{% endif -%}

[3D View and Download]({{ site.github.repository_url }}{{ site.stlurl }}{{ part.folder | uri_escape }}/{{ part.subFolder | uri_escape }}/{{part.fileName | uri_escape}}){: .btn .btn--inverse}
{: .text-center}

*Description:*  {{ part.description }} 

*Notes:*  {{ part.notes }}

*Print Profile:*  [{{ part.print}}]({{ site.baseurl }}/docs/printing/#print-settings)

---
{:style="clear: left"} 

{% endif %}

{% endfor %}

### Accessory Mounts
Various accessory mounts have been designed for sensors and companion computers.  There are also some generic mounts that are very helpful to complete a build.

*Print Profile:*  [Solid]({{ site.baseurl }}/docs/printing/#print-settings)

[View and download mounts here](https://github.com/goodrobots/devFrame/tree/master/stl/Accessory%20Mounts)


## Carbon Fiber Tubes
The devFrame requires the use of roll wrapped carbon fiber tubes.  They are not very cheap but they are very strong and light.  We are using metric tube sizes to help with international sourcing of tubes.  See our [Resource page]({{ site.baseurl }}/docs/resources/#carbon-fiber-tube) for more tube details.

### Sizes 
- 10mm carbon fiber tubes are used for the box frame, and arms for smaller builds 
- 12mm carbon fiber tubes are used for the arms of larger builds 

Each build will list the details of tube lengths and sizes used, but in general two 500mm lengths *each* of 10mm and 12mm should be enough to build a 450 class devFrame.

**Caution** -- Using pultruded carbon fiber tubes is not supported as the clamping force created by the clamps can cause failure of the tube, and the frame itself.
{: .notice--info}

## Fasteners
![Fastner Overview]({{site.baseurl}}/assets/images/frame-details/fastener-overview.jpeg){: width="40%" .align-left} The devFrame has been designed to use common fasteners to the maximum extent possible.  Pan head screws in various sizes should be available at any hardware store.

Note -- Fastener nomenclature can be confusing.  The devFrame is intended to be used with pan head screws with a pointed end and Phillips drive style.  They are sometimes called sheet metal screws or self tapping.
{: .notice--primary}

### Sizes
- #6 x 1in for Box Ends
- #6 x 3/4in for Arm Mounts
- #4 x 1/2in for Accessory Mounts

The detailed build documentation should call out the size and quantity of fastener required for each step in building the frame.

Most sensors and companion computers can be mounted with #2 or #4 screws, depending on mounting hole size. 

There are some sensors that have small mounting holes and will require #0/M1.5 screws.  These can be a bit harder to find at local stores.  If you are having a hard time finding them check for eye glass repair kits as they often include small screws.

### Imperial to Metric 

Gauge | Millimeter
--- | ---
#0 | 1.5
#1 | 1.8
#2 | 2.2
#3 | 2.5
#4 | 3
#6 | 3.5

Note -- Conversion from screw gauge to metric diameter may not be exact.  Clearance and pilot holes in the DevFrame should allow for either Imperial or Metric screws.  Some drilling for clearance holes may be required.
{: .notice--primary}