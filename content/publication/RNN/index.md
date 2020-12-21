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

abstract: We study the problem of GDP forecasting, introducing a neural network model that consistently outperforms state-of-the-art economic models. The model outperforms an autoregressive model with 2 lags (AR(2)), and a dynamic stochastic general equilibrium (DSGE) model over all horizons, a factor model on horizons longer than 2 periods ahead, and the median forecast of the Survey of Professional Forecasters at 5 quarters ahead. Forecasts over different time windows, model specifications, along with Monte Carlo simulations suggest the performance of our model is robust and reproducible. Additionally, our tests show performance does not depend significantly on initialization of parameters, reasonable changes in architecture, and noise due to stochastic optimization. Forecasts evaluation across countries also suggests this model is able to successfully forecast GDP across many different policy regimes, jointly.  
# Summary. An optional shortened abstract.
# summary: We use Recurrent Neural Networks to perform state-of-the-art forecasting of GDP, outperforming benchmark models like the AR(2), Smets-Wouters DSGE, and Factor Models.  
summary: We study the problem of GDP forecasting, introducing a neural network model that consistently outperforms state-of-the-art economic models. The model outperforms an autoregressive model with 2 lags (AR(2)), and a dynamic stochastic general equilibrium (DSGE) model over all horizons, a factor model on horizons longer than 2 periods ahead, and the median forecast of the Survey of Professional Forecasters at 5 quarters ahead. Forecasts over different time windows, model specifications, along with Monte Carlo simulations suggest the performance of our model is robust and reproducible. Additionally, our tests show performance does not depend significantly on initialization of parameters, reasonable changes in architecture, and noise due to stochastic optimization. Forecasts evaluation across countries also suggests this model is able to successfully forecast GDP across many different policy regimes, jointly.  
tags:
- Deep Learning
- Recurrent Neural Networks
- Time Series Econometrics
- Macroeconomic Forecasting
featured: true

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: '/files/RNN_GDP.pdf'
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: '/files/RNN_pres.pdf'
# url_source: '#'
url_video: https://youtu.be/5Qb5KoDYvTY

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
