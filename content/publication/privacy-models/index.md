---
title: "Specification and Operation of Privacy Models for Data Streams on the Edge"
authors:
- admin
- Ilir Murturi
- Schahram Dustdar
date: "2022-05-01T00:00:00Z"
doi: "10.1109/ICFEC54809.2022.00018"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE 6th International Conference on Fog and Edge Computing (ICFEC)"
publication_short: ""

abstract: The growing number of Internet of Things (IoT) devices generates massive amounts of diverse data, including personal or confidential information (i.e., sensory, images, etc.) that is not intended for public view. Traditionally, predefined privacy policies are usually enforced in resource-rich environments such as the cloud to protect sensitive information from being released. However, the massive amount of data streams, heterogeneous devices, and networks involved affects latency, and the possibility of having data intercepted grows as it travels away from the data source. Therefore, such data streams must be transformed on the IoT device or within available devices (i.e., edge devices) in its vicinity to ensure privacy. In this paper, we present a privacy-enforcing framework that transforms data streams on edge networks. We treat privacy close to the data source, using powerful edge devices to perform various operations to ensure privacy. Whenever an IoT device captures personal or confidential data, an edge gateway in the device’s vicinity analyzes and transforms data streams according to a predefined set of rules. How and when data is modified is defined precisely by a set of triggers and transformations - a privacy model - that directly represents a stakeholder’s privacy policies. Our work answered how to represent such privacy policies in a model and enforce transformations on the edge.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dsg.tuwien.ac.at/team/sd/papers/ICFEC_2022_I_Murturi_Specification.pdf
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
url_slides: 'uploads/Paper_PrivacyModel.pptx.pdf'
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Boris Sedlak**](https://www.researchgate.net/publication/361443377_Specification_and_Operation_of_Privacy_Models_for_Data_Streams_on_the_Edge)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [Master Thesis]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}
#slides: example
---
