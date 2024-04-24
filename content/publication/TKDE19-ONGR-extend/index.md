---
title: "Structured Graph Reconstruction for Scalabl Clustering"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - Junwei Han
  - Kai Xiong
  - Feiping Nie
  - Xuelong Li

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-10-01T00:00:00Z"
doi: "10.1109/TKDE.2019.2948850"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Knowledge and Data Engineering*
publication_short: In *TKDE*

abstract: Spectral clustering is a quite simple but effective method for solving graph clustering problem. It projects the original data points into a lower dimensional space with spectral embedding, and then relies on an algorithm to obtain the cluster labels. Since it involves eigen-decomposition of the graph Laplacian matrix for embedding, spectral clustering has high time complexity and is not able to process large scale data. The performance of spectral clustering is also limited by a post-processing algorithm such as kmeans. To tackle the two issues, we propose a method called Orthogonal and Nonnegative Graph Reconstruction (ONGR) for large scale clustering. The two constraints serve as a structure constraint with which the graph reconstructed by the indicator matrix is structured. The proposed method has linear time complexity with respect to the data size that it mainly needs to implicitly construct a graph and iteratively perform economical singular value decomposition for a small size matrix. Moreover, the interpretability of the indicator matrix is offered due to the nonnegative constraint, and thus our method can provide the cluster labels with no post-processing. The experiments on benchmark datasets show the effectiveness of the proposed scalable clustering method.

# Summary. An optional shortened abstract.
summary: we propose a method called Orthogonal and Nonnegative Graph Reconstruction (ONGR) for large scale clustering. This is an journal extension of the work published in conference IJCAI-2017.

tags: [large scale clustering, graph reconstruction]

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
