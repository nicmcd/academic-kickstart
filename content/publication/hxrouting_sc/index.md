---
title: "Practical and Efficient Incremental Adaptive Routing for HyperX Networks"
authors:
- admin
- Mikhail Isaev
- Adriana Flores
- Al Davis
- John Kim
date: "2019-11-17T00:00:00Z"
doi: "10.1145/3295500.3356151"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The International Conference for High Performance Computing, Networking, Storage, and Analysis 2019*
publication_short: In *SC19*

abstract: In efforts to increase performance and reduce cost, modern lowdiameter networks are designed for average case traffic and rely on non-minimal adaptive routing for network load-balancing when adversarial traffic patterns are encountered. Source adaptive routing is the predominant method for adaptive routing even though it presents many deficiencies related to making global decisions based solely on local information. In contrast, incremental adaptive routing, which performs an adaptive decision at every hop, is able to increase throughput and reduce latency by overcoming the deficiencies of source adaptive routing. We present two incremental adaptive routing algorithms for HyperX which are the first to be fully implementable in modern high-radix router architectures and interconnection network protocols. Using cycle accurate simulations of a 4,096 node network, our evaluation shows these algorithms are able to exceed the performance of prior work by as much as 4x with synthetic traffic and 25% with 27-point stencil traffic.

# Summary. An optional shortened abstract.
summary: We present two practical and efficient incremental adaptive routing algorithms for HyperX.

tags:
- Networks
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: pubs/nicmcdonald_hxrouting_sc_2019.pdf
url_slides: pubs/nicmcdonald_hxrouting_sc_2019_slides.pdf
#url_code:
#url_dataset:
#url_poster:
#url_project:
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- supersim

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!--
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
-->
