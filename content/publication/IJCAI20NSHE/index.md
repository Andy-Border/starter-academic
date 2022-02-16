---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Network Schema Preserving Heterogeneous Information Network Embedding"
authors: [Jianan Zhao, Xiao Wang, Chuan Shi, Zekuan Liu, Yanfang Ye]
date: 2020-04-21T10:54:51+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-08T10:54:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence"
publication_short: "IJCAI-20"

abstract: "As heterogeneous networks have become increasingly ubiquitous, Heterogeneous Information Network (HIN) embedding, aiming to project nodes into a low-dimensional space while preserving the heterogeneous structure, has drawn increasing attention in recent years. Many of the existing HIN embedding methods adopt meta-path guided random walk to retain both the semantics and structural correlations between different types of nodes. However, the selection of meta-paths is still an open problem, which either depends on domain knowledge or is learned from label information. As a uniform blueprint of HIN, the network schema comprehensively embraces the high-order structure and contains rich semantics. In this paper, we make the ﬁrst attempt to study network schema preserving HIN embedding, and propose a novel model named NSHE. In NSHE, a network schema sampling method is ﬁrst proposed to generate subgraphs (i.e., schema instances), and then multi-task learning task is built to preserve the heterogeneous structure of each schema instance. Besides preserving pairwise structure information, NSHE is able to retain high-order structure (i.e., network schema). Extensive experiments on three real-world datasets demonstrate that our proposed model NSHE significantly outperforms the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: "We propose to preserve network schema proximity in heterogeneous information network embedding."

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

url_pdf: http://shichuan.org/doc/87.pdf
url_code: https://github.com/Andy-Border/NSHE
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
  caption: "NSHE"
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
