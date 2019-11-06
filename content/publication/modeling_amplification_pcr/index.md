+++
title = "Modeling the Amplification of Immunoglobulins through Machine Learning on Sequence-Specific Features"
date = 2019-07-24
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matthias Döring", "Christoph Kreer", "Nathalie Lehnen", "Florian Klein", "Nico Pfeifer"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Scientific Reports*."
publication_short = "In *Scientific Reports*"

# Abstract and optional shortened version.
abstract = "Successful primer design for polymerase chain reaction (PCR) hinges on the ability to identify primers that efficiently amplify template sequences. Here, we generated a novel Taq PCR data set that reports the amplification status for pairs of primers and templates from a reference set of 47 immunoglobulin heavy chain variable sequences and 20 primers. Using logistic regression, we developed TMM, a model for predicting whether a primer amplifies a template given their nucleotide sequences. The model suggests that the free energy of annealing, ΔG, is the key driver of amplification (p = 7.35e-12) and that 3′ mismatches should be considered in dependence on ΔG and the mismatch closest to the 3′ terminus (p = 1.67e-05). We validated TMM by comparing its estimates with those from the thermodynamic model of DECIPHER (DE) and a model based solely on the free energy of annealing (FE). TMM outperformed the other approaches in terms of the area under the receiver operating characteristic curve (TMM: 0.953, FE: 0.941, DE: 0.896). TMM can improve primer design and is freely available via openPrimeR (http://openPrimeR.mpi-inf.mpg.de)."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["geno2pheno-hiv2]"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.nature.com/articles/s41598-019-47173-w.pdf"
url_project = "https://openPrimeR.mpi-inf.mpg.de"

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
