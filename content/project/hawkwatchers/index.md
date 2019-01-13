+++
title = "Hawkwatchers"
date = 2018-03-25
draft = false
share = false
profile = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-learning", "natural-language-processing", "social-science"]

# Project summary to display on homepage.
summary = "Predicting the US Federal Reserve interest rate using Fed press releases."

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
 url_custom = [{icon_pack = "fab", icon="github", name="Code", url = "https://github.com/jgdenby/hawkwatchers"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
## Description
Hawkwatchers is a project that aims to predict the direction of the United States Federal Reserve interest rate based on the content and tone of its [press releases](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm). Through several iterations of data formulation and model selection, the final model was able to correctly predict 87% of interest rate changes between 2016 and 2018.
