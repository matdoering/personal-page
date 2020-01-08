+++
title = "Identification and Analysis of Methylation Call Differences between Bisulfite Microarray and Bisulfite Sequencing Data with Statistical Learning Techniques"
date = 2014-06-12
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
    abstract = "Methylation of DNA is an epigenetic modification known to play a prime role in gene silencing and is an important topic in epigenetic research. Although accurate methods for measuring DNA methylation exist, technology-dependent errors give rise to inconsistencies between method results. We studied DNA methylation measurements from the Infinium HumanMethylation450 microarray and whole genome bisulfite sequencing to evaluate whether there are locus-specific measurement differences and whether this effect is predictable using statistical learning techniques. The ability to determine inconsistent methylation measurements based on bisulfite-converted sequencing data alone would be valuable for epigenome-wide association studies, in which such positions could be excluded. We built support vector regression models based on Illumina bisulfite-sequencing data of HepaRGd7R2 to predict. A measure for read similarity was obtained via numerical and string kernels as well as set kernels. We introduced the notion of hybrid string kernels to afford a similarity measure for both, numeric and string input simultaneously. Feature importance was analyzed using kernel-target alignment and positional oligomer importance matrices. Using a read-based set kernel, we found that the predicted values correlated significantly with the observed outcomes. This model made use of CpG positions, which implicitly code for the sample’s methylation. To obtain a model independent of whole-genome methylation, we excluded the CpG positions and still found a significant correlation. Features beside the reads played only a minuscule role in the emergence of inconsistent methylation measurements. To our knowledge, this is the first time someone was able to show that differences are predictable from the sequence, hinting at the over- or underestimation of methylation status for specific loci using either technique."

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
url_pdf = "identification_and_analysis_doering_2014.pdf"

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
