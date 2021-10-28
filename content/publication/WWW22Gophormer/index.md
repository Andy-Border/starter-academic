---
# Documentation: https://wowchemy.com/docs/managing-content/


title: "Gophormer: Ego-Graph Transformer for Node Classification"
authors: [Jianan Zhao, Chaozhuo Li, Qianlong Wen, Yiqi Wang, Yuming Liu, Hao Sun, Xing Xie, Yanfang Ye]
date: 2021-10-26T08:03:00-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-26T08:03:00-05:00


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "https://arxiv.org/abs/2110.13094"
publication_short: "Arxiv PrePrint"

abstract: "Transformers have achieved remarkable performance in a myriad of fields including natural language processing and computer vision. However, when it comes to the graph mining area, where graph neural network (GNN) has been the dominant paradigm, transformers haven’t achieved competitive performance, especially on the node classification task. Existing graph transformer models typically adopt fully-connected attention mechanism on the whole input graph and thus suffer from severe scalability issues and are intractable to train in data insufficient cases. To alleviate these issues, we propose a novel Gophormer model which applies transformers on ego-graphs instead of full-graphs. Specifically, Node2Seq module is proposed to sample ego-graphs as the input of transformers, which alleviates the challenge of scalability and serves as an effective data augmentation technique to boost model performance. Moreover, different from the feature-based attention strategy in vanilla transformers, we propose a proximity-enhanced attention mechanism to capture the fine-grained structural bias. In order to handle the uncertainty introduced by the ego-graph sampling, we further propose a consistency regularization and a multi-sample inference strategy for stabilized training and testing, respectively. Extensive experiments on six benchmark datasets are conducted to demonstrate the superiority of Gophormer over existing graph transformers and popular GNNs, revealing the promising future of graph transformers."

# Summary. An optional shortened abstract.
summary: "We propose Gophormer with Node2Seq and Proximity-Enhanced-Attention modules. Gophormer outperforms existing graph transformers with a large margin on node classification task."

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

url_pdf: https://arxiv.org/pdf/2110.13094.pdf
url_code: 
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
