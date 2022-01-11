---
title: "Cascaded SE-ResUnet for segmentation of thoracic organs at risk"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bohan Yu
- Biwen Lei
- Haochao Ying
- Xiao Zhang 
- Danny Z. Chen
- Jian Wu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-12-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.neucom.2020.08.086"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Neurocomputing
publication_short: Neurocomputing

abstract: Computed Tomography (CT) has been widely used in the planning of radiation therapy, which is one of the most effective clinical lung cancer treatment options. Accurate segmentation of organs at risk (OARs) in thoracic CT images is a key step for radiotherapy planning to prevent healthy organs from getting over irradiation. However, known automatic image segmentation methods can hardly yield desired OAR delineation results, while manual delineation tends to take long time and tedious effort. In this paper, we propose a novel deep learning network, called cascaded SE-ResUnet, for automatic segmentation of thoracic organs including left lung, right lung, heart, esophagus, trachea, and spinal cord. Speciﬁcally, we ﬁrst use a coarse segmentation network to identify the regions of interest (ROIs), and then a ﬁne segmentation network is applied to achieve reﬁned segmentation results, organ by organ. Finally, different conﬁgured models are ensembled to obtain the ﬁnal segmentation results. In the StructSeg 2019 Challenge, we showed the capability of our new framework and won the 1st place at the test phase. Our code is available open-source at https://github.com/zjuybh/StructSeg2019.

# Summary. An optional shortened abstract.
summary: CT Segmentation of five thoracic organs.

tags: ['medical imaging']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S092523122100093X'
url_code: 'https://github.com/zjuybh/StructSeg2019'
url_dataset: 'https://structseg2019.grand-challenge.org'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects:
- Medical Image Analysis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
