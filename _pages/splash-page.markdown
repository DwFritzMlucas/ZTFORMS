---
title: ZeroTouch Knowledge Base
layout: home
classes:
  - landing
  - wide
sidebar:
  nav: "splash_sidebar_nav"
permalink: / #/splash-page/
toc: true
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/splash/yamaha.jpg
  actions:
    - label: "Download Aether"
      url: "/pages/markdownQuickRef/"
excerpt: "How can we help you? This site provides step by step instructions on how to get started with the 
Aether software, the ZeroTouch tool, and its metrology environment." 
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'


feature_row_one:
  - image_path: /assets/images/splash/gettingstarted.png
    title: "Getting Started"
    excerpt: "Downloading, installing, and general set up of the Aether software environment."
    url: "/pages/gettingstarted/"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/solidload.png
    title: "Loading a Solid"
    excerpt: "Loading and orienting the Part Assembly in the workspace."
    url: "/pages/intermediate_loadandorient"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/pippart_1.png
    title: "Building a PIP"
    excerpt: "Building a Part Inspection Program (PIP) with the Inspection Operations List"
    url: "/pages/intermediate_diagnostic"
    btn_label: "Read More"
    btn_class: "btn--secondar"

feature_row_two:
  - image_path: /assets/images/splash/alignment.png
    title: "On Tool Alignments"
    excerpt: "Creating an Alignment Routine within the PIP"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/simulate.png
    title: "Simulating"
    excerpt: "Simulation, Collision Detection, and Virtual Point Clouds"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/tool_gaugeBLK.png
    title: "Aquiring Data"
    excerpt: "Simulation, Collision Detection, and Virtual Point Clouds"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"

feature_row_three:
  - image_path: /assets/images/splash/sensor_laser.png
    title: "Sensors"
    excerpt: "An Exhaustive description of sensors in the ZeroTouch Catalog"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/analysis.png
    title: "Analysis"
    excerpt: "Evaluation of point clouds and basic metrology in general "
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/calibration.png
    title: "Diagnostics"
    excerpt: "Standard Tests, Inspections, and Evaluations"
    url: "/pages/intermediate_diagnostic"
    btn_label: "Read More"
    btn_class: "btn--secondar"

#feature_row_left:
#  - image_path: /assets/images/splash/RobotHead_Square.png
#    title: "Left aligned placeholder 1"
#    excerpt: "Left-aligned image centered with"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"

#feature_row_right:
#  - image_path: /assets/images/splash/ZTCube.jpg
#    title: "Placeholder 1"
#    excerpt: "Right-aligned image with ``"
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
 
---
{% include feature_row id="feature_row_one"%}
{% include feature_row id="feature_row_two"%}
{% include feature_row id="feature_row_three"%}