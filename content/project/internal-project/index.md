---
title: High-fidelity wind modelling
summary: A mathematical framework to computer-generate wind data that look like real data
draft: true 
tags:
- Data-driven modelling
date: "2020-04-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Aliquam in turpis accumsan, malesuada nibh ut, hendrerit justo. Cum sociis
natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
Quisque sed erat nec justo posuere suscipit. Donec ut efficitur arcu, in
malesuada neque. Nunc dignissim nisl massa, id vulputate nunc pretium nec.
Quisque eget urna in risus suscipit ultricies. Pellentesque odio odio, tincidunt
in eleifend sed, posuere a diam. Nam gravida nisl convallis semper elementum.
Morbi vitae felis faucibus, vulputate orci placerat, aliquet nisi. Aliquam erat
volutpat. Maecenas sagittis pulvinar purus, sed porta quam laoreet at. 

The increasing sophistication of wind turbine design and control generates a need for high-quality data. Therefore, the relatively limited set of measured wind data needs to be extended with computer-generated surrogate data, e.g. to make reliable statistical studies of energy production and mechanical loads. Surrogate data should realistically reflect the full scale of possible wind conditions. First, the surrogate data should conform to the same statistical descriptors as measured physical data (in particular the amplitude distribution and the frequency spectrum). There are methods that can handle this. A far bigger challenge is non-stationarity, reflected by the variation of wind conditions on distinct temporal scales (such as daily or seasonal variations). No existing method can fully capture this non-stationarity. Furthermore, wind data are three-dimensional, in the sense that information about the wind direction is as important as information about the wind speed. 

---
