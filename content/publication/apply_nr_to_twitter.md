+++
title = "Applying a Passive Network Reconstruction Technique to Twitter Data in Order to Identify Trend Setters"
date = 2017-08-09T23:29:58-10:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Vasu Chetty", "Nathan Woodbury", "Jacob Brewer","Kenneth Lee", "Sean Warnick"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "2017 IEEE Conference on Control Technology and Applications"
publication_short = "IEEE CCTA"

# Abstract and optional shortened version.
abstract = "In this work we apply a systems-theoretic approach to identifying trend setters on Twitter. A network reconstruction algorithm was applied to Twitter data to determine causal relationships among topics discussed by popular Twitter users. Causal relationships in this context means that the topics tweeted by a single user influences the topics tweeted by another user, regardless of sentiment. A user that causally influences other users, without themselves being strongly influenced is identified as a trendsetter. This work seeks to identify potential trendsetters among popular Twitter users and demonstrating that causal influence does not always directly correlate with a user's popularity in terms of followers-demonstrating that popularity alone may not be sufficient for identifying trendsetters on Twitter."
abstract_short = "In this work we apply a systems-theoretic approach to identifying trend setters on Twitter."

# Featured image thumbnail (optional)
image_preview = "network.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["network reconstruction","social network", "system theory"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/8062645/"
url_preprint = ""
url_code = "https://gitlab.com/idealabs/twitter-paper"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Conference Link", url = "http://ccta2017.ieeecss.org/"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/network.png"
caption = "The relative magnitude of links reconstructed by the reconstruction algorithm on the Twitter data."

+++
