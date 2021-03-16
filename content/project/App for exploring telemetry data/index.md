---
title: App for exploration of acoustic telemetry data.

summary: This application implements Unsupervised Machine Learning (UML) methods to explore acoustic telemetry data. Code was written in R, and the application was developed using R Shiny. 

tags:
  - Machine Learning
  - Principal Component Analysis (PCA)
  - Hierarchical Clustering 
  - Acoustic Telemetry
  - R Shiny
  
date: "2021-03-16"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Hierarchical clustering result based on data from my project.
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Source code
  url: https://github.com/dijiagberien/ExpFishBehavApp/blob/main/ExpFishBehav/app.R

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

<iframe src="https://adogbejiagberien.shinyapps.io/ExpFishBehav/?_ga=2.31131519.158181347.1615873406-553828022.1615873406" width=700 height=900"></iframe>

Spatial ecology can be described as the study of an organism's relationship with its environment, and among its goals, it aims to guide decision-making related to conservation. Technological developments of tools such as biotelemetry has been central to the success of spatial ecology; we have begun to acquire data at rapid rates across broad spatial scales.

For my MSc. thesis, I analyzed acoustic telemetry data acquired in Toronto Harbour. Publication soon to come, and the associated code is on my github page. Following results of the analysis, I further decided to develop the code into an application, perhaps other individuals working with acoustic telemetry data may find it useful. 

Click on the [source code](https://github.com/dijiagberien/ExpFishBehavApp/blob/main/ExpFishBehav/app.R) to have a look at the methods utilized in building this tool. Essentially, moving averages and weighted averages are independently applied on the telemetry data, after which the hierarchical clustering is used to find receiver and fish clusters in the data set. Overtime, the goal is to incorporate environmental data analysis into the app. and find relationships between your tagged organisms and their environment. Additionally, more user control will be provided so users may select what algorithms to implement, the time scale of their data to analyze, The hope is to develop the project based on needs of end users. 
