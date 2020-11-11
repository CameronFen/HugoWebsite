---
title: "GDP Forecasting using Recurrent Neural Networks"
authors:
- Cameron Fen and Samir Undavia
date: "2020-11-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Despite the big data and machine learning revolution, thus far, the standard models like auto-regressive models are still consistently used as a baseline. We introduce our neural network model along with a data augmentation strategy that allows our model to be competitive and outperform state-of-the-art models beyond 2 quarters ahead. We compare our model with the AR(2), the Smets Wouters DSGE, and a factor model which forms an "efficient" frontier of economic forecasting performance among all models tested. Our forecasts over the the longest time period, 5 quarters ahead, consistently outperforms the median forecast of the Survey of Professional Forecasters. Forecasts over different time windows, model specifications, along with Monte Carlo simulation suggests the performance of our model is robust, reproducible, and does not depend significantly on the randomness of the initialization and numerical optimization.  

# Summary. An optional shortened abstract.
summary: We use Recurrent Neural Networks to perform state-of-the-art forecasting of GDP, outperforming benchmark models like the AR(2), Smets-Wouters DSGE, and Factor Models.  
tags:
- Deep Learning
- Recurrent Neural Networks
- Time Series Econometrics
- Macroeconomic Forecasting
featured: true

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
