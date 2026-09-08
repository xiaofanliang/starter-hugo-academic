---
title: "Governing AI’s Footprint: A Scalable Human-AI Workflow to Extract Zoning Codes for Data Centers and Renewable Energy Sitting"
summary: How are data centers and solar farms regulated in zoning codes in the Midwest? How can we use AI to read and extract zoning codes related to their sitting? 
 
tags:
- Urban Analytics
- Urban AI
date: "2025-08-26"

# Optional external URL for project (replaces project detail page).
# external_link: "https://github.com/xiaofanliang/AeroATLGreenway"

image:
  caption: Proposed data center by UM and Los Alamos National Laboratory (image from the web)
  focal_point: Smart

links:

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

(In Progress)

This work is in development with Zhixuan Qi, Sarah Mills. 

**Abstract**

As generative AI systems drive demand for computational infrastructure, their societal impacts increasingly intersect with environmental strain, land use conflict, and opaque regulatory frameworks. Data centers consume vast energy and water resources, while facing fragmented, outdated, and inconsistent zoning regulations. Similarly, renewable energy facilities intended to offset these environmental costs are hindered by slow permitting processes and ambiguous land use designations. Although both are critical to supporting AI systems, the siting and permitting processes for data centers and renewables remain opaque to researchers, industries, and policy makers. 

At the center of this challenge are zoning ordinances, the key legal instruments that regulate land use in every U.S. jurisdiction. These documents define permitted uses, spatial constraints, and development conditions—but they are decentralized, heterogeneous, and written in complex legal logic that jumps across sections. As a result, answering even a basic question—Where are data centers allowed? What restrictions apply to solar farms?—requires manually reviewing hundreds of lengthy PDF ordinances. Traditional rule-based extraction methods cannot keep pace with this complexity, and manual review is infeasible at scale.

To address this gap, we propose an agentic pipeline to extract structured information from zoning codes related to renewable energy facilities as included in the EnergyZoning database. Our aims include:

- Design and evaluate an agentic pipeline and human-AI workflow for high-validity extraction of zoning information from complex, heterogeneous legal documents.

- Evaluate performance of the pipeline against EnergyZoning database.

- Evaluate the performance of the pipeline on a variety of queries varying in inferential and professional complexity on a single document, to examine the boundary between machine capability and human professional judgement. 

- Discuss lessons learned for a universal computational infrastructure for making zoning accessible and comparable at scale. 

By transforming unstructured zoning ordinances into machine-interpretable, human-navigable knowledge systems, this project aims to make zoning more transparent, accessible, and analytically tractable. The resulting datasets and tools will support immediate planning needs in the Midwest and provide a scalable blueprint for responsible AI-era land-use governance—ensuring that infrastructure development remains sustainable, publicly accountable, and aligned with community and environmental priorities.

[PROJECT STATUS UPDATE] We will probably not have enough capacity to cover the data center extraction since we don't have ready-to-go ground-truth information, but Liang is applying for additional funding to continue the tasks. 

This project is funded by MIDAS PODS and Microsoft. 

**Keywords: data center; renewable energy; zoning; AI governance**

