---
title: "Is Your Neighbor Your Friend? Scan Methods for Spatial Social Network (SSN) Hotspot Detection"
summary: How do you find clusters of incidents/individuals that are not only geographically close to each other, but also have dense local social connections? 
tags:
- Spatial Social Networks
date: "2023-11-18"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The result of EdgeScan using a 1km euclidean distance moving window
  focal_point: Smart


links:
- name: Tutorial 
  url: "https://friendlycities-gatech.github.io/SSN_tutorial/advanced-ssn-metrics.html#ssn-hot-spot-detection"
- name: R package 
  url: "https://github.com/friendlycities-gatech/SSNtools"
- name: PDF 
  url: "publication/hotspots/SSNHotspots.pdf"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

This work is developed with Dr. Clio Andris, Joshua Baker, and Dr. Daniel Della Posta. 

**Abstract** 

In GIS, we use moving window and hot spot detection to analyze point patterns within a given area. Such methods can detect clusters of point events such as concentration of crime incidences or disease incidences. Yet, these methods do not account for the connections between individuals but instead only find clusters of points.

Here, we share two GIS methods, EdgeScan and NDScan, for capturing areas with high and low levels of local social connections. Both methods are moving window processes that count the number of edges and network density, respectively, for each node in a given focal area (window area). We implement these methods on a case study of 1960s connections between members of the Mafia in New York City with various definitions of a focal neighborhood (e.g., Euclidean, K Nearest Neighbor etc.). These methods successfully capture focal areas where Mafia members are highly connected, yet differ from traditional spatial hot spots derived through point patterns. 

To make our methods publicly available, we published the EdgeScan and NDScan algorithms in the `SSNtools` [R package](https://github.com/friendlycities-gatech/SSNtools) and provided examples to replicate such analyses to other studies in a bookdown [tutorial](https://friendlycities-gatech.github.io/SSN_tutorial/advanced-ssn-metrics.html#ssn-hot-spot-detection).  

