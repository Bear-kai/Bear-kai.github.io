---
title: "Regularized and Constrained Self-representation for Robust Feature Selection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kai Xiong
  - Feiping Nie
  - Junwei Han

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: unpublished
publication_short: unpublished

abstract: Feature selection is an important topic in data mining. In this paper, we focus on the problem in unsupervised scenario, which is challenging due to the absence of labels. We formulate our model RRCS from the viewpoint of selfrepresentation. For the selection matrix, unlike many previous methods which take the L2,1-norm regularization to avoid trivial solution and achieve feature selection, we directly use the L2,0-norm constraint to obtain a more accurate solution. By explicitly considering the representation residue, we relax the hard linear constraint in self-representation, making our model better deal with the nonlinear case. Using the L2,1- norm loss term, the robustness of RRCS is achieved. Moreover, we add a graph regularization to preserve the local structure of the original data. An efficient algorithm is derived to solve the regularized and constrained problem. Extensive experiments on several datasets demonstrate the effectiveness of the proposed method.

# Summary. An optional shortened abstract.
# summary: ''

tags: [feature selection, self-representation]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''  # add local file
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
  preview_only: true # false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---



<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
