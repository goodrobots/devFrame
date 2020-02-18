---
title: "Contribute"
permalink: /contribute/
---
## Background
The devFrame is [licensed under the CERN OHL](https://github.com/goodrobots/devFrame/blob/master/License.md).  It is Open Source Hardware and intended to be hacked on.  However, it is still difficult to collaborate on an open source hardware project due to a lack of free tools and open file formats for parametric modeling.  The situation is getting better, but, for now, the easiest thing to do is to use a [GitHub workflow](https://guides.github.com/introduction/flow/) to clone the project and submit a pull request.   Just keep in mind that GitHub is not optmized for hardware project collaboration.  But we can make it work.

## Making The Docs Better
If you have found typos, or spelling errors, or find something confusing in the docs please let us know by [filing an issue](https://github.com/goodrobots/devFrame/issues).  Creating the docs for this project took longer than designing the frame.  They are a key part to making this project useful, so please do let us know if you find any issues.  All devFrame docs live in the /docs folder and we are happy to accept Pull Requests for fixing spelling, broken links, etc. 

## Designing New Parts
The devFrame has [standardized interfaces]({{ site.baseurl }}/docs/frame-details/#interfaces).  Like an API we will try very hard not to change the interface specs so you can design new mounts and accessories to these standards.  We have provided all parts in both stl and step format.  Step format is intented for those who would like to import into 3D CAD software for modification.  Please export any new parts in both stl and step formats for any Pull Requests.  

## Hosting Community Builds
If you have built and tested a devFrame we would really like to host the details.  It's one of our primary goals.  Most of the data in our build section is pulled from Google Sheets.  So if you can type a bit of information in a spreadsheet we can bring it into the site here for others to benefit.  Expect more details on this process as we refine the site and the workflow to contribute.  For now, a link to a short YouTube video and a copy of your parameter files is a great start. 

## Pull Requests

New to git?  Have a look at [GitHub Flow](https://guides.github.com/introduction/flow/)

To submit a pull request:

1. [Clone the repo](https://github.com/goodrobots/devFrame)
2. Create a branch off of master and give it a meaningful name such as my-new-sensor-mount
3. Commit your changes to your new branch
4. Push your changes to your new branch
5. [Open a pull request on GitHub](https://github.com/goodrobots/devFrame/pulls)