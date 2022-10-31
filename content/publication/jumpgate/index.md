---
title: "Jumpgate: Automating Integration of Network Connected Accelerators"
authors:
- Craig Mustard
- Swati Goswami
- admin
- Joel Nider
- Ivan Beschastnikh
- Alexandra (Sasha) Fedorova

date: "2021-07-01T00:00:00Z"
doi: "10.1145/3456727.3463770"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SYSTOR '21"
publication_short: ""

abstract: Network-connected accelerators (NCA), such as programmable switches, ASICs, and FPGAs can speed up operations in data analytics. But so far, integration of NCAs into data analytics systems required manual effort.We present Jumpgate, a system that simplifies integration of existing NCA code into data analytics systems, such as Apache Spark or Presto. Jumpgate places most of the integration code into the analytics system, which needs to be written once, leaving NCA programmers to write only a couple hundred lines of code to integrate new NCAs. Jumpgate relies on dataflow graphs that most analytics systems use internally, and takes care of the invocation of NCAs, the necessary format conversion, and orchestration of their execution via novel staged network pipelines.Our implementation of Jumpgate in Apache Spark made it possible, for the first time, to study the benefits and drawbacks of using NCAs across the entire range of queries in the TPC-DS benchmark. Since we lack hardware that can accelerate all analytics operations, we implemented NCAs in software. We report on how and when analytics workloads will benefit from NCAs to motivate future designs.

# Summary. An optional shortened abstract.
summary:

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1145/3456727.3463770
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
