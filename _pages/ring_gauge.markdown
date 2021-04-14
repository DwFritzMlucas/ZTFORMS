---
layout: single
title: Ring Gauge Diagnostic
permalink: /pages/ring_gauge/
---
<h3> Introduction</h3> 

Using a ring gauge is a simple way to gain some immediate understanding of how well your tool is performing. The ring gauges involved here use the inner diameter as the NIST traceable characteristic. Ring gauges are easily purchased on-line and come in a wide variety of diameters.  In addition to the inner diameter, this Inspection Program uses the top surface as an additional measurementm plane. Ring gauges are almost all NIST traceable. We’ve purchased our from Mitutoyo and it came with a certificate and a stamp on the side noting the inner diameter down to the micron.  For this specific Diagnostic we will use a 40 mm ring gauge, Mitutoyo part number 177-290.

<p align="center">
  <img width="250" height="250" src="/assets/images/ringgauge/partnumber.png">
</p>

The gauge above can be purchased from Amazon at the following link:

[Mitutoyo 177-290 Amazon](https://www.amazon.com/Mitutoyo-177-290-Diameter-1-5Micrometer-Accuracy/dp/B001D7DQCS)


<h3>The Fixture</h3> 

ZeroTouch Engineers have designed a printable fixture to hold the gauge above. The Fixture uses some clamps to hold it securely during inspection along with some other small hardware noted in the Bill of Materials.

<p align="center">
  <img width="400" height="400" src="/assets/images/ringgauge/ringgauge_assy.png">
</p>

The Size Adapter noted above is only used if a different ring gauge is inserted and wont be needed if the 40 mm gauge above is used. The links below will provide downloads of the STEP file and the Bill of Materials, or if desired simply contact DWFritz to purchase one. 

[STEP File](https://www.amazon.com/Mitutoyo-177-290-Diameter-1-5Micrometer-Accuracy/dp/B001D7DQCS)

[Bill of Materials](https://www.amazon.com/Mitutoyo-177-290-Diameter-1-5Micrometer-Accuracy/dp/B001D7DQCS)

<h3>Aquisition Directions</h3>
Let's assume you have the 40 mm ring gauge, and the assembled fixture above. Place the fixture on the tools platen as shown below. Make sure to align the pins and to not over tighten the screws into the platen. 

Clean the ring gauge before inserting the gauge into the fixture. The plastic container that holds the gauge in the box often come with some silicon gel like substance in them. This can get on the gauge and interfere with the resulting measuements. simply wipe the gauge down (INSIDE AND OUTSIDE) with a cloth wipe. 

<p align="center">
  <img width="250" height="250" src="/assets/images/ringgauge/clean_me.png">
</p>

Place the ring gauge - dimension stamp side down - into the fixture. Note that printed parts like the fixture can involve a wide tolerance band. Center the ring as much as possible into the fixture.  The clamps work through deflection. They can can be deflected by pressing down on them close to their posts. 

<p align="center">
  <img width="400" height="400" src="/assets/images/ringgauge/ringon_platen.png">
</p>

Depending on your machines sensor package, copy the appropriate workspace from one of the links below. If the machine usea a 90 confocal use the specified link, if a 90 deg Proteus sensor is installed, use the other one.  

[Package with 90 Confcal](https://www.amazon.com/Mitutoyo-177-290-Diameter-1-5Micrometer-Accuracy/dp/B001D7DQCS)

[Package with 90 Proteus](https://www.amazon.com/Mitutoyo-177-290-Diameter-1-5Micrometer-Accuracy/dp/B001D7DQCS)

Start up Aether and load the workspace. Dont start the PIP yet, there are a few things we need to discuss.

The PIP performs an alignment using the top surface (3 stamp patterns with the confocal 0) and the internal diameter with the appropriate 90 deg sensor (Confocal or Proteus). After Alignment, the PIP will re-inspect the three patterns on the top surface with the confocal 0 sensor. The internal ring is then re-inspected with the appropriate 90 deg sensor. This will be followed by the bridge rotating the phi angle to -90 and using the 90 deg sensor to inspect the same top three surface stamp patterns. Finally, a single top stanp is inspected using the 0 deg confocal. 

The NIST traceable characteristic on the ring gauge is the internal diameter. The PIP measures this with the 90 deg sensor. The top surface is measured with the 0 deg confocal and the 90 deg sensor. We're interested in the difference between what we measured the inner diameter as and what the **actual** diameter is, *and* the difference between the plane made form the top surface as collected with the 0 deg Confocal and that made with data collected with the 90 deg sensor. 

Perform a final visual inspection making sure the ring is in the center of the gauge.  Select the Online Inspection, Press StartZT, and run the PIP for 5 cycles. Note that you'll have to tell Aether where to put the poutput data.  It will take approximately 20 minutes to complete the fice cycles, get a cup of coffee and go do somework. 

When done grab the output files (.PSL's and .XML's) form where you asked Aether to store them, and evaluate. 

-----------------------------------------------

The PIP is set up to request automatic evaluation of the collected point clouds upon finishing.      



 



Adjust the PIP to "point to your MServer"