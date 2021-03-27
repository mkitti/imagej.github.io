---
autogenerated: true
title: 3D Viewer › Surface Plot
layout: page
categories: 
description: test description
---

(Return to the [Developer Documentation](3D_Viewer__Developer_Documentation) page)  
(Return to the main [3D\_Viewer](3D_Viewer) page)

How to work with surface plots
------------------------------

You can download example source code for this HowTo [here](3D_Viewer__Example_code).

Before reading this HowTo, it may be helpful to read [The relation between Content and Universe](3D_Viewer__Content_Structure).

Surface plots show a 2D image as a 3D plot, where the 3rd dimension is given by the intensity.

Because only one slice of an image stack can be displayed a time, `SurfacePlot2D` offers a method to set the displayed slice:

        // Add the image as a volume
        Content c = univ.addSurfacePlot(imp);


        // Retrieve the SurfacePlotGroup
        SurfacePlotGroup splot = (SurfacePlotGroup)c.getContent();

        // Scroll through the slices
        for(int i = 0; i &lt; 15; i++) {
            splot.setSlice(i + 1);

        }