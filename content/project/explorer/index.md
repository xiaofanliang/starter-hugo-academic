---
title: "Place social diversity explorer"
summary: A D3 explorer to show the racial and income diversity of people visiting point of interests in Atlanta.
tags:
- Digital Civics and Critical Data
date: "2022-01-02"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Poster
  focal_point: Smart

links:
- name: Interactive Explorer 
  url: "https://github.gatech.edu/pages/vvangala3/PlaceSocialDiversityExplorer/"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

The Place Social Diversity Explorer is a class project in CSE6242 Data Analytics and Visualization with Yifeng Wang, Uijeong Hwang, and Varun Vangala. Uijeong and I are responsible for the front end (D3) development of the explorer. 

Explore the income and racial diversity of places in Atlanta [here](https://github.gatech.edu/pages/vvangala3/PlaceSocialDiversityExplorer/)! A place is more diverse if the visitors to a place come from neighborhoods with various income and racial backgrounds. A dot in the map represents a place and the color represents social diversity. 

We calculate income or racial diversity score through the same methods. First, we estimate the race or income composition of visitors at each POI by the average of the compositions in their origin block groups. Second, we calculate the income or racial diversity score as the sum of deviations from the city average.

The explorer built on top of a project in Friendly Cities Lab that estimate diversity at POIs in Atlanta Georgia using origin-destination data (see project [here](http://friendlycities.gatech.edu/projects/estimating-diversity-at-points-of-interest-pois-in-atlanta-georgia-using-origin-destination-trip-data/.)). 


