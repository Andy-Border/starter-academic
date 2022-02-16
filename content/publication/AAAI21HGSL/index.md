---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Heterogeneous Graph Structure Learning for Graph Neural Networks"
authors: [Jianan Zhao, Xiao Wang, Chuan Shi, Binbin Hu, Guojie Song, Yanfang Ye]
date: 2020-12-08T10:57:44+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-07T10:57:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The Thirty-Fifth AAAI Conference on Artificial Intelligence"
publication_short: "AAAI-21"

abstract: "Heterogeneous Graph Neural Networks (HGNNs) have drawn increasing attention in recent years and achieved outstanding performance in many tasks. The success of the existing HGNNs relies on one fundamental assumption, i.e., the original heterogeneous graph structure is reliable. However, this assumption is usually unrealistic, since the heterogeneous graph in reality is inevitably noisy or incomplete. Therefore, it is vital to learn the heterogeneous graph structure for HGNNs rather than rely only on the raw graph structure. In light of this, we make the first attempt towards learning an optimal heterogeneous graph structure for HGNNs and propose a novel framework HGSL, which jointly performs Heterogeneous Graph Structure Learning and GNN parameter learning for classification. Different from traditional homogeneous graph structure learning, considering the heterogeneity of different relations in heterogeneous graph, HGSL generates each relation subgraph separately. Specifically, in each generated relation subgraph, HGSL not only considers the feature similarity by generating feature similarity graph, but also considers the complex heterogeneous interactions in features and semantics by generating feature propagation graph and semantic graph. Then, these graphs are fused to a learned heterogeneous graph and optimized together with a GNN towards classification objective. Extensive experiments on real-world graphs demonstrate that the proposed framework significantly outperforms the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: "We propose a Heterogeneous Graph Structure Learning (HGSL) framework to learn optimal heterogeneous graph structures (for downstream tasks) for GNNs."

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

url_pdf: https://github.com/Andy-Border/HGSL/blob/main/paper/AAAI21%20HGSL%20Camera%20Ready%20vFinal.pdf
url_code: https://github.com/Andy-Border/AAAI21-HGSL
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
  caption: "HGSL"
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
