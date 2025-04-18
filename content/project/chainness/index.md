---
title: "Measuring McCities: Landscapes of Chain and Independent Restaurants in the United States"
summary: Which cities most resemble McCities? What kinds of built environment and sociodemographic characteristics are associated with the prevelance of chain restaurants?
tags:
- Urban Analytics
date: "2021-06-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Average Chain Percentage in Urbanized Areas
  focal_point: Smart

links:
- name: Washington Post
  url: https://www.washingtonpost.com/business/2022/09/29/chain-restaurant-capitals/?pwapi_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWJpZCI6IjMxMTY0NDc1IiwicmVhc29uIjoiZ2lmdCIsIm5iZiI6MTY2NDUzNjIzMCwiaXNzIjoic3Vic2NyaXB0aW9ucyIsImV4cCI6MTY2NTc0NTgzMCwiaWF0IjoxNjY0NTM2MjMwLCJqdGkiOiJmZjlmZDI4Zi1lYjRmLTRmZGEtODY1NS0xNzlkNmZmYzlmYzkiLCJ1cmwiOiJodHRwczovL3d3dy53YXNoaW5ndG9ucG9zdC5jb20vYnVzaW5lc3MvMjAyMi8wOS8yOS9jaGFpbi1yZXN0YXVyYW50LWNhcGl0YWxzLyJ9._tx8XDmZWM4JI-p6dUyVioU7T6imoddZPJowNCS8ryE
- name: Interactive Map
  url: https://friendlycities-gatech.github.io/chainness/
- name: PDF 
  url: https://www.dropbox.com/s/ajlduy88l8oqc5i/ChainRestaurants.pdf?dl=0
- name: Data
  url: https://github.com/friendlycities-gatech/chainness

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
This work is completed with Dr. Clio Andris. 

View interactive data dashboard [HERE](https://friendlycities-gatech.github.io/chainness/). 
View restaurant dataset [HERE](https://github.com/friendlycities-gatech/chainness). 

This project was featured by the [Washington Post](https://www.washingtonpost.com/business/2022/09/29/chain-restaurant-capitals/?pwapi_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWJpZCI6IjMxMTY0NDc1IiwicmVhc29uIjoiZ2lmdCIsIm5iZiI6MTY2NDUzNjIzMCwiaXNzIjoic3Vic2NyaXB0aW9ucyIsImV4cCI6MTY2NTc0NTgzMCwiaWF0IjoxNjY0NTM2MjMwLCJqdGkiOiJmZjlmZDI4Zi1lYjRmLTRmZGEtODY1NS0xNzlkNmZmYzlmYzkiLCJ1cmwiOiJodHRwczovL3d3dy53YXNoaW5ndG9ucG9zdC5jb20vYnVzaW5lc3MvMjAyMi8wOS8yOS9jaGFpbi1yZXN0YXVyYW50LWNhcGl0YWxzLyJ9._tx8XDmZWM4JI-p6dUyVioU7T6imoddZPJowNCS8ryE), [CNN](https://www.cnn.com/videos/politics/2022/10/08/smr-chain-restaurant-regions-vote-trump.cnn), [Bloomberg](https://www.bloomberg.com/news/newsletters/2021-06-16/maplab-how-many-chain-restaurants-are-in-your-city), [FiveThirtyEight](https://fivethirtyeight.com/features/the-datasets-were-looking-at-this-week-21/), and [Georgia Public Broadcasting](https://www.gpb.org/news/2022/10/06/which-states-have-the-most-chain-restaurants-georgia-tech-researchers-map-it-out). 

In this research, we explored which (types of) places have an independent food culture and which resemble McCities: foodscapes where the food offerings in the landscape can be found just as easily in one place as in many other (often distant) places. We used a dataset of nearly 800,000 independent and chain restaurants for the contiguous United States and defined a chain restaurant using multiple methods. We performed a descriptive analysis of chainness prevalence at the urban area and metropolitan area level. We also identified socioeconomic and infrastructural factors that correlate with high or low “chainness” (a value indicating the likelihood of finding the same venue elsewhere) by combining a random forest model and linear regression. We then examined chainness variation across census tracts with similar sociodemographic values. Using common GIS operations, we evaluated the likelihood of finding chain restaurants of nearby water bodies, coastlines, and highway ramps.

We found that car-dependent small towns, low walkability, a high percentage of African American residents or Trump voters, college towns, and close distance to highways were associated with high chainness. These places tended to be prevalent in the Midwestern and the Southeastern U.S. Independent restaurants were associated with high pedestrian walkability, high population density, Asian, Hispanic and majority-White neighborhoods, tourist areas, areas with urban professionals, and retirement communities. They were also found in coastal cities and waterfronts. These findings, paired with the contribution of a method that quantifies ‘chainness’, opens new pathways for studying landscapes through the lens of commercialism and the service economy. 
