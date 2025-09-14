---
title: "Exploring biological motion perception in two-stream convolutional neural networks"
authors:
- admin
- Hannah Lee
- Tianmin Shu
- Hongjing Lu
date: "2021-01-07T00:00:00Z"
doi: "https://doi.org/10.1016/j.visres.2020.09.005"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Vision Research"
publication_short: "Vision Res"

abstract: "Visual recognition of biological motion recruits form and motion processes supported by both dorsal and ventral pathways. This neural architecture inspired the two-stream convolutional neural network (CNN) model, which includes a spatial CNN to process appearance information in a sequence of image frames, a temporal CNN to process optical flow information, and a fusion network to integrate the features extracted by the two CNNs and make final decisions about action recognition. In five simulations, we compared the CNN model's performance with classical findings in biological motion perception. The CNNs trained with raw RGB action videos showed weak performance in recognizing point-light actions. Additional transfer training with actions shown in other display formats (e.g., skeletal) was necessary for CNNs to recognize point-light actions. The CNN models exhibited largely viewpoint-dependent recognition of actions, with a limited ability to generalize to viewpoints close to the training views. The CNNs predicted the inversion effect in the presence of global body configuration, but failed to predict the inversion effect driven solely by local motion signals. The CNNs provided a qualitative account of some behavioral results observed in human biological motion perception for fine discrimination tasks with noisy inputs, such as point-light actions with disrupted local motion signals, and walking actions with temporally misaligned motion cues. However, these successes are limited by the CNNs' lack of adaptive integration for form and motion processes, and failure to incorporate specialized mechanisms (e.g., a life detector) as well as top-down influences on biological motion perception."

# Summary. An optional shortened abstract.
summary: TBD.

tags:
- Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0042698920301656?via%3Dihub'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
