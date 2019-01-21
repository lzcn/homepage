+++
title = "Sampling for Approximate Maximum Search in Factorized Tensor"
date = 2017-08-19
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Zhi Lu**", "Yang Hu", "Bing Zeng"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]
publication = "International Joint Conference on Artificial Intelligence"
publication_short = "IJCAI"

abstract = """
Factorization models have been extensively used for recovering the missing entries of a matrix or tensor. However, directly computing all of the entries using the learned factorization models is prohibitive when the size of the matrix/tensor is large. On the other hand, in many applications, such as collaborative filtering, we are only interested in a few entries that are the largest among them. In this work, we propose a sampling-based approach for finding the top entries of a tensor which is decomposed by the *CANDECOMP/PARAFAC* model. We develop an algorithm to sample the entries with probabilities proportional to their values. We further extend it to make the sampling proportional to the k-th power of the values, amplifying the focus on the top ones. We provide theoretical analysis of the sampling algorithm and evaluate its performance on several real-world data sets. Experimental results indicate that the proposed approach is orders of magnitude faster than exhaustive computing. When applied to the special case of searching in a matrix, it also requires fewer samples than the other state-of-the-art method.
"""
abstract_short = "In this work, we propose a sampling-based approach for finding the top entries of a tensor which is decomposed by the CP model."
# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Citations: 7", url = "https://scholar.google.com/scholar?cites=4825604373906396874"}]

# Digital Object Identifier (DOI)
# doi = "10.1093/gji/ggu044"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++