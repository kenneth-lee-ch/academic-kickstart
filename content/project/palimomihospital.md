+++
title = "Predict Patient Inflow at Pali Momi Hospital’s Emergency Room"
date = 2018-08-10T00:49:52-10:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["data-analysis","prediction"]

# Project summary to display on homepage.
summary = "This project predicts the patient inflow at Pali Momi Hospital's Emergency Room (ER) and provides recommendations for how to optimize scheduling for their ER's doctors and mid-level providers."

# Optional image to display on homepage.
image_preview = "correlation.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

We use R and Jupyter Notebook in making predictions models to understand patient influx and predict their arrival times. Using these predictions, we can aid Pali Momi hospital in understanding what factors cause over and understaffing. Therefore, we can more positively help Pali Momi hospital to meet patient demand. 

To enhance the given data from the hospital and provide more accurate predictions, we add the following features and variables: 1. Number of walk-ins 2. Airplane passenger arrival counts from the past two years from international and domestic individuals 3. Month of year, week of year 4. Scheduling periods 5. Doctor-to-patient ratio.

In this work, we use repeated cross-validation with 10 folds and 3 repeats, a common standard configuration for comparing models by estimating the model accuracy.  Repeated K-fold Cross-Validation method involves splitting the dataset into k-subsets. Each subset is held-out while the model is trained on all other subsets. This process is repeated until accuracy is determined for each instance in the dataset, and an overall accuracy estimate is provided. 




 

