---
title: Predict Patient Inflow at Pali Momi Hospital’s Emergency Room
summary: This project predicts the patient inflow at Pali Momi Hospital's Emergency Room (ER) and provides recommendations for how to optimize scheduling for their ER's doctors and mid-level providers.

tags:
- Machine Learning
- Regression
- Data Science
date: "2018-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The correlation among all the variables we use for the project.
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/kenneth-lee-ch
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We use R and Jupyter Notebook in making predictions models to understand patient influx and predict their arrival times. Using these predictions, we can aid Pali Momi hospital in understanding what factors cause over and understaffing. Therefore, we can more positively help Pali Momi hospital to meet patient demand. 

To enhance the given data from the hospital and provide more accurate predictions, we add the following features and variables: 1. Number of walk-ins 2. Airplane passenger arrival counts from the past two years from international and domestic individuals 3. Month of year, week of year 4. Scheduling periods 5. Doctor-to-patient ratio.

In this work, we use repeated cross-validation with 10 folds and 3 repeats, a common standard configuration for comparing models by estimating the model accuracy.  Repeated K-fold Cross-Validation method involves splitting the dataset into k-subsets. Each subset is held-out while the model is trained on all other subsets. This process is repeated until accuracy is determined for each instance in the dataset, and an overall accuracy estimate is provided. 
