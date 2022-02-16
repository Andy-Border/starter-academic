---
# Documentation: https://wowchemy.com/docs/managing-content/


title: "Multi-View Self-Supervised Heterogeneous Graph Embedding"
authors: [Jianan Zhao, Qianlong Wen, Shiyu Sun, Yanfang Ye, Chuxu Zhang]
date: 2021-09-19T08:03:00-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-19T08:03:00-05:00


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases 2021"
publication_short: "ECML/PKDD-21"

abstract: "Graph mining tasks often suffer from the lack of supervision from labeled information due to the intrinsic sparseness of graphs and the high cost of manual annotation. To alleviate this issue, inspired by recent advances of self-supervised learning (SSL) on computer vision and natural language processing, graph self-supervised learning methods have been proposed and achieved remarkable performance by utilizing unlabeled information. However, most existing graph SSL methods focus on homogeneous graphs, ignoring the ubiquitous heterogeneity of real-world graphs where nodes and edges are of multiple types. Therefore, directly applying existing graph SSL methods to heterogeneous graphs can not fully capture the rich semantics and their correlations in heterogeneous graphs. In light of this, we investigate self-supervised learning on heterogeneous graphs and propose a novel model named Multi-View Self-supervised heterogeneous graph Embedding (MVSE). By encoding information from different views defined by meta-paths and optimizing both intra-view and inter-view contrastive learning tasks, MVSE comprehensively utilizes unlabeled information and learns node embeddings. Extensive experiments are conducted on various tasks to show the effectiveness of the proposed framework."

# Summary. An optional shortened abstract.
summary: "We propose a multi-view contrastive learning heterogeneous graph embedding method MVSE to capture the intra- and inter-semantics of heterogeneous graphs in a self-supervised manner."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://2021.ecmlpkdd.org/wp-content/uploads/2021/07/sub_408.pdf
url_code: https://github.com/Andy-Border/MVSE
url_dataset: 
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "MVSE"
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
slides: ""
---
