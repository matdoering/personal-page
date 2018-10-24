+++
title = "A genotypic method for determining HIV-2 coreceptor usage enables epidemiological studies and clinical decision support"
date = 2016-12-20
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Matthias Döring", "Pedro Borrego", "Joachim Büch", "Andreia Martins", "Georg Friedrich", "Ricardo Jorge Camacho", "Josef Eberle", "Rolf Kaiser", "Thomas Lengauer", "Nuno Taveira", "Nico Pfeifer"]

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
publication = "In *Retrovirology*."
publication_short = "In *Retrovirology*"

# Abstract and optional shortened version.
abstract = "CCR5-coreceptor antagonists can be used for treating HIV-2 infected individuals. Before initiating treatment with coreceptor antagonists, viral coreceptor usage should be determined to ensure that the virus can use only the CCR5 coreceptor (R5) and cannot evade the drug by using the CXCR4 coreceptor (X4-capable). However, until now, no online tool for the genotypic identification of HIV-2 coreceptor usage had been available. Furthermore, there is a lack of knowledge on the determinants of HIV-2 coreceptor usage. Therefore, we developed a data-driven web service for the prediction of HIV-2 coreceptor usage from the V3 loop of the HIV-2 glycoprotein and used the tool to identify novel discriminatory features of X4-capable variants. Using 10 runs of tenfold cross validation, we selected a linear support vector machine (SVM) as the model for geno2pheno[coreceptor-hiv2], because it outperformed the other SVMs with an area under the ROC curve (AUC) of 0.95. We found that SVMs were highly accurate in identifying HIV-2 coreceptor usage, attaining sensitivities of 73.5% and specificities of 96% during tenfold nested cross validation. The predictive performance of SVMs was not significantly different (p value 0.37) from an existing rules-based approach. Moreover, geno2pheno[coreceptor-hiv2] achieved a predictive accuracy of 100% and outperformed the existing approach on an independent data set containing nine new isolates with corresponding phenotypic measurements of coreceptor usage. geno2pheno[coreceptor-hiv2] could not only reproduce the established markers of CXCR4-usage, but also revealed novel markers: the substitutions 27K, 15G, and 8S were significantly predictive of CXCR4 usage. Furthermore, SVMs trained on the amino-acid sequences of the V1 and V2 loops were also quite accurate in predicting coreceptor usage (AUCs of 0.84 and 0.65, respectively). In this study, we developed geno2pheno[coreceptor-hiv2], the first online tool for the prediction of HIV-2 coreceptor usage from the V3 loop. Using our method, we identified novel amino-acid markers of X4-capable variants in the V3 loop and found that HIV-2 coreceptor usage is also influenced by the V1/V2 region. The tool can aid clinicians in deciding whether coreceptor antagonists such as maraviroc are a treatment option and enables epidemiological studies investigating HIV-2 coreceptor usage. geno2pheno[coreceptor-hiv2] is freely available at http://coreceptor-hiv2.geno2pheno.org."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["geno2pheno-hiv2]"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://retrovirology.biomedcentral.com/track/pdf/10.1186/s12977-016-0320-7"
url_poster = "/g2p_coreceptor-hiv2_glasgow_2016.pdf"

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
