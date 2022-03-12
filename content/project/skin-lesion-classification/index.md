---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Skin Lesion Classification"
subtitle: Early detecion of skin cancer with Convolutional Neural Networks and Dermoscopic Imaging
summary: ""
authors: [Agnieszka Mikolajczyk, Arkadiusz Kwasigroch, Michal Grochowski]
tags: [Deep Learning, Image Analtysis, Medicine, projects]
categories: []
date: 2020-01-20T16:11:19+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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

In the last twenty years the interest of automated skin lesion classification dynamically increased partially because of public datasets appearing. Automated computer-aided skin cancer detection in dermatoscopic images is a very challenging task due to uneven
datasets sizes, the huge intra-class variation with small interclass variation, and numerous artifacts. During my work on the project I approached the problem in two ways:
* with hand-crafted features based on extended ABCD rule and a shallow neural network,
* with Convolutional Neural Networks.

![ISIC Challenge 2019](https://workshop2018.isic-archive.com/images/task3.png)
