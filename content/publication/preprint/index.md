---
title: "HDGL: A hierarchical dynamic graph representation learning model
for brain disorder classification"
authors:
- admin
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The human brain can be considered as complex networks, 
composed of various regions that continuously exchange their information with each other, forming the brain network graph, from which
nodes and edges are extracted using resting-state functional magnetic resonance imaging (rs-fMRI).
Therefore, this graph can potentially depict abnormal patterns that have emerged under the influence of
brain disorders. So far, numerous studies have attempted to find embeddings for brain network graphs
and subsequently classify samples with brain disorders from healthy ones, which include limitations
such as: not considering the relationship between samples, not utilizing phenotype information, lack of
temporal analysis, using static functional connectivity (FC) instead of dynamic ones and using a fixed
graph structure. We propose a hierarchical dynamic graph representation learning (HDGL) model,
which is the first model designed to address all the aforementioned challenges. HDGL consists of
two levels, where at the first level, it constructs brain network graphs and learns their spatial and
temporal embeddings, and at the second level, it forms population graphs and performs classification
after embedding learning. Furthermore, based on how these two levels are trained, four methods
have been introduced, some of which are suggested for reducing memory complexity. We evaluated
the performance of the proposed model on the ABIDE and ADHD-200 datasets, and the results
indicate the improvement of this model compared to several state-of-the-art models in terms of various
evaluation metrics.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
