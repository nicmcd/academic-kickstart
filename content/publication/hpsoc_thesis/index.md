---
title: "High-Performance Service-Oriented Computing"
authors:
- admin
- Bill Dally
date: "2016-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "" #2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "*Stanford University*"
publication_short: ""

abstract: This dissertation presents Sikker, a highly-scalable high-performance distributed system architecture for secure service-oriented computing. Sikker includes a novel service-oriented application model upon which security and isolation policies are derived and enforced. The workhorse of Sikker is a custom network interface controller, called the Network Management Unit (NMU), that enforces Sikker’s security and isolation policies while providing high-performance network access. Sikker’s application model satisfies the complex interactions of modern large-scale distributed applications. Experimental results show that even when implemented on very large clusters, the NMU adds a negligible message latency of 41 ns under realistic workloads and 91 ns at the 99:99th percentile of worst-case access patterns. Analysis shows that the NMU can support many hundreds of Gbps of bandwidth with common VLSI technologies while imposing zero overhead on the CPU. Integrated into Sikker and the NMU is a novel service-oriented, distributed rate-control algorithm, called Sender-Enforced Token and Rate Exchange (SE-TRE), that is able to regulate service-to-service aggregate rates while imposing zero latency overhead at the 99:99th percentile, less than 0.3% bandwidth overhead, and zero overhead on the CPU. Sikker’s service-oriented security and isolation methodology removes high overheads imposed by current systems. Sikker allows distributed applications to operate in an environment with fine-grained security and isolation while experiencing supercomputer-like network performance.

# Summary. An optional shortened abstract.
summary: This dissertation presents Sikker, a highly-scalable high-performance distributed system architecture for secure service-oriented computing.

tags:
- Distributed Computing
- Networks
- Security
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: pubs/nicmcdonald_hpsoc_stanford_2016.pdf
url_slides: pubs/nicmcdonald_hpsoc_stanford_2016_slides.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
