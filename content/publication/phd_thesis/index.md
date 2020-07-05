+++
title = "Computational approaches for improving treatment and prevention of viral infections"
date = 2019-06-12
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matthias Döring"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Abstract and optional shortened version.
    abstract = """The treatment of infections with HIV or HCV is challenging. Thus, novel drugs and new computational approaches that support the selection of therapies are required. This work presents methods that support therapy selection as well as methods that advance novel antiviral treatments.

geno2pheno[ngs-freq] identifies drug resistance from HIV-1 or HCV samples that were subjected to next-generation sequencing by interpreting their sequences either via support vector machines or a rules-based approach. geno2pheno[coreceptor-hiv2] determines the coreceptor that is used for viral cell entry by analyzing a segment of the HIV-2 surface protein with a support vector machine. openPrimeR is capable of finding optimal combinations of primers for multiplex polymerase chain reaction by solving a set cover problem and accessing a new logistic regression model for determining amplification events arising from polymerase chain reaction.

geno2pheno[ngs-freq] and geno2pheno[coreceptor-hiv2] enable the personalization of antiviral treatments and support clinical decision making. The application of openPrimeR on human immunoglobulin sequences has resulted in novel primer sets that improve the isolation of broadly neutralizing antibodies against HIV-1. The methods that were developed in this work thus constitute important contributions towards improving the prevention and treatment of viral infectious diseases."""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["geno2pheno-ngs"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "computational_approaches_doering_2019.pdf"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
