+++
title = "geno2pheno [ngs-freq]: a genotypic interpretation system for identifying viral drug resistance using next-generation sequencing data"
date = 2018-05-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matthias Döring", "Joachim Büch", "Georg Friedrich", "Alejandro Pironti", "Prabhav Kalaghatgi", "Elena Knops", "Eva Heger", "Martin Obermeier", "Martin Däumer", "Alexander Thielen", "Rolf Kaiser", "Thomas Lengauer", "Nico Pfeifer"]

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
publication = "In *Nucleic Acids Research*."
publication_short = "In *Nucleic Acids Research*"

# Abstract and optional shortened version.
    abstract = """Identifying resistance to antiretroviral drugs is crucial for ensuring the successful treatment of patients infected with viruses such as human immunodeficiency virus (HIV) or hepatitis C virus (HCV). In contrast to Sanger sequencing, next-generation sequencing (NGS) can detect resistance mutations in minority populations. Thus, genotypic resistance testing based on NGS data can offer novel, treatment-relevant insights.

Since existing web services for analyzing resistance in NGS samples are subject to long processing times and follow strictly rules-based approaches, we developed geno2pheno[ngs-freq], a web service for rapidly identifying drug resistance in HIV-1 and HCV samples. By relying on frequency files that provide the read counts of nucleotides or codons along a viral genome, the time-intensive step of processing raw NGS data is eliminated. Once a frequency file has been uploaded, consensus sequences are generated for a set of user-defined prevalence cutoffs, such that the constructed sequences contain only those nucleotides whose codon prevalence exceeds a given cutoff. After locally aligning the sequences to a set of references, resistance is predicted using the well-established approaches of geno2pheno[resistance] and geno2pheno[hcv].

geno2pheno[ngs-freq] can assist clinical decision making by enabling users to explore resistance in viral populations with different abundances and is freely available at http://ngs.geno2pheno.org."""

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
url_pdf = "https://academic.oup.com/nar/article-pdf/46/W1/W271/25110528/gky349.pdf"
url_poster = "/geno2pheno_ngs-freq.pdf"
url_project = "https://ngs.geno2pheno.org"

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
