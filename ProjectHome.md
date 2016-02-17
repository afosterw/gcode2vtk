This program is able to convert your 3d printing gcode to the vtk file format. This file format you can then use to visualize your paths in e.g. paraview

In the download, you will find a pre-compiled windows version, and the source.
It should compile just by old-fashinoned "make".

You can even create animations: Start with a tube filter, then create a threshold of the filament1. View->Animation. Add a new animation property "threshold->upper level". let it run from 0 to max. set the frames to 1000, and press play.

http://www.youtube.com/watch?v=erWtMVjbHAU

# Usage: #
In windows,  you extract it an put in a folder useful to you, e.g. c:\Programs\gcode2vtk

You right click any gcode file, say open or open with, choose program, and browse for
"c:\Programs\gcode2vtk\gcode2vtk.exe".

Then any time you double click a gcode file, it will be converted to
a ".gcode.vtk" file.

# Examples #

right click-> view image, to get an unscaled version.

![http://kariert.org/gcode2vtk/gcode2vtk_a.png](http://kariert.org/gcode2vtk/gcode2vtk_a.png)
![http://kariert.org/gcode2vtk/gcode2vtk_b.png](http://kariert.org/gcode2vtk/gcode2vtk_b.png)
![http://kariert.org/gcode2vtk/gcode2vtk_c.png](http://kariert.org/gcode2vtk/gcode2vtk_c.png)