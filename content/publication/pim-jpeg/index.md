---
title: "Bulk JPEG Decoding on In-Memory Processors"
authors:
- Joel Nider
- Jackson Dagger
- admin
- Daniel Ng
- Alexandra (Sasha) Fedorova

author_notes:
- 
date: "2022-07-01T00:00:00Z"
doi: "10.1145/3534056.3534946"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SYSTOR '22"
publication_short: ""

abstract: JPEG is a common encoding format for digital images. Applications that process large numbers of images can be accelerated by decoding multiple images concurrently. We examine the suitability of using a large array of in-memory processors (PIM) to obtain a high throughput of decoding. The main drawback of PIM processors is that they do not have the same architectural features that are commonly found on CPUs such as floating point, vector units and hardware-managed caches. Despite the lack of features, we demonstrate that it is feasible to build a JPEG decoder for PIM, and evaluate its quality and potential speedup. We show that the quality of decoded images is sufficient for real applications, and there is a significant potential for accelerating image decoding for those applications. We share our experiences in building such a decoder, and the challenges we faced while doing so.

# Summary. An optional shortened abstract.
summary:

tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1145/3534056.3534946
url_code: 'https://github.com/UBC-ECE-Sasha/PIM-JPEG'
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
