---
layout: single
title: Loading and Orienting a Part
permalink: /pages/loadandorient/
---
Let's begin by downloading the STEP file listed below. This file represents an assembly containing a
Gauge Block and an a holding fixture. 

[DOWNLOAD GAUGE BLOCK ASSEMBLY]({{ site.baseurl }}{% link /assets/supportfiles/loadandorient/gauge_block_assy.STEP %})

Once the file has been downloaded, save it off to a folder that can be easily acccessed. 
Load up Aether on your laptop or PC.  Once the software has loaded, choose the "IMPORT CAD" button on the 
WORKSPACE dialog (upper left area). Browse to the location where the STEP file above was saved, select it, and press the load button.  The part should load into the view port as shown in the figure below. At this point, the user is asked to differentiate between the part and the fixture (the solid holding the part) by selecting the part - see the dialog on the right side of the screen. Select the rectangular gauge block geometry by clicking on it with the mouse in the viewport. It should turn blue.  If you select the wrong object, simply push the "Select None" button and everything will be deselected.  Additonally, note that the entire assembly can be selected using the "Select All" button. For this tutorial select the rectangular gauge block and then push the "Import" button. 
<p align="center">
  <img width="600" height="400" src="/assets/images/loadandorient/loadsolid.png">
</p>

Congratulations, the part, along with it's fixture, has been loaded into Aether. However there is more to do.
The next step is to re-orient the assembly. The goal is to orient the part in the same manner as it is to be scanned in the tool. At this point the user is presented with the EDIT CAD dialog located on the right side of the screen.  The current part orientation is rotated -90 degrees about the X axis. Why negative?  In science (which includes metrology) he standard is toto use somehtin called *the right hand rule*. Point the thumb oy your right hand (not your left) down the X axis in the positive direction, the way the rest of your fingers curl into your hand is noted as positive. Seriously, dont use your left. The part is rotated in opposite (negative) direction.
<p align="center">
  <img width="200" height="300" src="/assets/images/loadandorient/rhrule.png">
</p>
 
 The plan for this part is to locate the bottom disk of the fixture flat on the top surface of the platen. The platen surface is represented by the grid pattern.  Consequenlty, a positive 90 deg rotation of the assembly around the X axis is required.
 in the EDIT CAD dialog, under Transform CAD, select the "Rotate" option, type 90 into the XX entry, making sure there are no other numbers entered into the TransformCAD dialog enries, and press the "Transform" button. 
<p align="center">
  <img width="600" height="400" src="/assets/images/loadandorient/rot90.png">
</p>

Note that the assembly rotated so the fixture is now setting with it's disk upon the grid/platen. Additionally note that the yellow Collision Avoidance Zone needs to be adjusted. The Collision Avoidance Zone is a zone whos outer surface area is used to map the "Link Passes" associated with our inspections. You'll learn more about this later. For now, simply understand that the outer surface of the Collision Avoidance Zone is used to move sensors around the part - making sure they dont run into anything. Push the "AutoFit" button in the Collision Avoidance Zone dialog. This will automatically fit the zone around the extent of the parts geometry. The box geometry can also be manually adjusted using the slider bars if desired. 
Another option would be to change the Collision Avoidance Zone from a box into a sphere using the "Shape" drop down in the dialog.   
<p align="center">
  <img width="600" height="400" src="/assets/images/loadandorient/spherecollitionzone.png">
</p>

The Spherical Avoidance zones center is located at the centroid of the part. Note that the only adjustment for the sphere is the diameter slider. 

 Let's raise the part up in the Z axis 25 mm to become more familiar with the part transformation process. Clear any entries in the Transform CAD dialog. Enter 25 into the Z axis entry, select the "Translation" option and push the Transform button. 
 The part should have raise up off the grid by 25 mm. 
 <p align="center">
  <img width="600" height="400" src="/assets/images/loadandorient/elevate25.png">
</p>

Let's put the part back on the grid by entering -25 in the Z axis entry (making sure the other entries are clear), choose the Translate option and push the Transform button. The part should have moved back down in Z and be placed on the grid now. 
Note that what we're really doing here is telling the ZeroTouch tool where the part will be in machine tool coordinates. 
If we had left the part 25mm up in Z, but in reality placed the part on the platen, the tool would not be able to scan the part correctly.

Regardless of the type of zone chosen, when done, push the "Close" button at the bottom right of the screen. If further modification is needed (we'll see this in other tutorials) simply select the "EDIT CAD" button in the upper left of the screen to show the EDIT CAD dialog again. 

Congratulations are in order. You've loaded, re-oriented, and adjusted the Collison Avoidance Zone on your first part. Save your workspace using the "File" drop down menu located in the upper left of the screen. Note that the workspace will now include a copy of the CAD file along with all the settings and orientation changes we've made above. Nice work. 
