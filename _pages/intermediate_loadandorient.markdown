---
layout: single
title: Loading and Orienting a Part Solid
permalink: /pages/intermediate_loadandorient/


feature_row_a:
  - image_path: /assets/images/splash/solidload.png
    title: "Step by step with a Gauge Block"
    excerpt: "A simple step by step load and orientation of a gauge block solid file"
    url: "/pages/loadandorient/"
    btn_label: "Gauge Block"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/gettingstarted.png
    title: "Something more Complicated"
    excerpt: "How to perform a moe complicated load and orientation."
    url: "/pages/ring_gauge"
    btn_label: "Ring Gauge"
    btn_class: "btn--secondar"
---

These tutorials will walk you through the loading and if needed, the re-orienting of a part in the Aether software. There are two tutorials here, a simple gauge block to start out with and the other involves something more complicated.

The first step in our workflow is to load a part file. As is often the case, it is entirely possible that the
CAD system that created the part used a different coordinate system orientation than is defined in the Aether software. Aether's default coordinate system is oriented with the ZeroTouch machine coordinate system and is show below. As the user faces the tool, the X axis points toward the right, the Y axis points toward the back of the machine, and the Z axis points toward the ceiling.  The origin of the tools coordinate system is located at the center of the platen when it is in the center of the machine as shown.  The platen rotates about the theta axis and the metrology bridge rotates about the phi axis.
<p align="center">
  <img width="600" height="600" src="/assets/images/loadandorient/toolcoordsys.png">
</p>

Becoming familiar with this coordinate system orientation will help the user as we progress through the following tutorials. It's important to understand the tool.


{% include feature_row id="feature_row_a"%}

