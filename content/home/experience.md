+++
# Experience widget.
widget = "experience"  # Do not modify this line!
active = true  # Activate this widget? true/false

title = "Experience"
subtitle = ""

# Order that this section will appear in.
weight = 8

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "January 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
title = "Software Architect"
company = "DB Systel"
company_url = "https://www.dbsystel.de"
location = "Frankfurt/Main"
date_start = "2019-02-01"
date_end = ""
description = """
I am currently working on a project that aims at optimizing the usage of the German railroad infrastructure.
"""

[[experience]]
  title = "Researcher in Bioinformatics"
  company = "Max Planck Institute for Informatics"
  company_url = "http://www.mpi-inf.mpg.de"
  location = "Saarbrücken"
  date_start = "2014-09-01"
  date_end = "2019-01-31"
  description = """
During my PhD, I worked as a researcher at the department of [Computational Biology & Applied algorithmics](https://bioinf.mpi-inf.mpg.de/) at the Max Planck Institute for Informatics. As a member of the [Statistical Learning in Computational Group](https://slcb.mpi-inf.mpg.de/), the focus of my work was on the development of machine learning methods that can assist the fight against viral infections such as HIV. 

In my work, I was involved in evaluating two clinical studies. For the EucoHIV project, which studies the efficacy of maraviroc treatment in Europe, I computed descriptive statistics and visualizations of quantities of interest such as CD4 cell counts, viral loads, and treatment success. To report the current status of the analysis, I created several comprehensive summaries of the results using Latex. For an [epidemiological study on
  HCV](https://www.sciencedirect.com/science/article/pii/S1386653216301123), I was responsible for the statistical analyses of the data using log-linear models.

Having attended a meeting of the [HIV-2EU study group](https://academic.oup.com/cid/article/56/11/1654/303269), I became aware of the problem of HIV-2 coreceptor prediction. After I had collected pairs of viral sequences and tropism assay measurements, I began developing a support vector machine for predicting HIV-2 coreceptor usage. Using R, I processed the data, engineered relevant features, performed model selection, and deployed the model (C++/PHP) in terms of the [geno2pheno[coreceptor-hiv2] web service](https://coreceptor-hiv2.geno2pheno.org/). 
  
My responsibilities also included calling drug resistance mutations using next-generation sequencing (NGS) data. For this purpose, I maintained and extended an NGS pipeline (Python/R) for the determination of HBV/[HCV resistance mutations](https://aasldpubs.onlinelibrary.wiley.com/doi/full/10.1002/hep.28255). Based on this experience, I developed the [geno2pheno[ngs-freq] web server](https://ngs.geno2pheno.org/) (C++/JavaScript), which can be used to identify minor resistance variants in HIV-1 and HCV using the algorithms of geno2pheno[resistance] and geno2pheno[hcv], respectively. The development of the tool was guided by the experts in the field, particularly those from the [Institute of Virology in Cologne](http://virologie.uk-koeln.de/).

Finally, I developed [openPrimeR](http://openprimer.mpi-inf.mpg.de/), a new multiplex primer design tool that is suitable for the amplification of highly mutated antibodies against HIV-1, which evolved through close collaboration with [Florian Klein's group](https://klein-lab.de/). The work resulted in two R packages that were released at Bioconductor, the [openPrimeR package](https://bioconductor.org/packages/release/bioc/html/openPrimeR.html) as well as the [openPrimeRui package](https://bioconductor.org/packages/release/bioc/html/openPrimeRui.html), which provides a frontend using the Shiny framework.

In summary: 
  
* Using machine learning, I developed two treatment decision support systems, which are used in clinical practice
* I developed a new tool for multiplex primer design with which novel antibodies against HIV-1 were identified
* I was involved in the statistical analysis for two clinical studies
* I maintained and extended a NGS processing pipeline for identifying drug resistance mutations
  """

[[experience]]
  title = "Fitness Trainer"
  company = "Uni-Fit"
  company_url = "http://www.uni-saarland.de"
  location = "Saarbrücken"
  date_start = "2014-04-01"
  date_end = "2018-09-01"
  description = """
As a trainer at the university's gym, my responsibilities included supervision of introductory courses and personal training.
"""

[[experience]]
  title = "Mentor"
  company = "Saarland University"
  company_url = "http://www.uni-saarland.de"
  location = "Saarbrücken"
  date_start = "2012-10-01"
  date_end = "2012-07-30"
  description = """
As a mentor, I was responsibe for assisting new Bioinformatics students arriving at university.
"""

[[experience]]
  title = "Software Development Intern"
  company = "Miaplaza"
  company_url = "https://www.miaplaza.com/"
  location = "Menlo Park (California)"
  date_start = "2012-06-01"
  date_end = "2012-09-30"
  description = """
As a software development intern, I worked on an [e-learning platform](http://www.alwaysicecream.com) using C# and was involved in game development using ImpactJS.
"""

[[experience]]
  title = "Scientific Assistant"
  company = "Max Planck Institute for Informatics"
  company_url = "http://www.mpi-inf.mpg.de"
  location = "Saarbrücken"
  date_start = "2011-10-01"
  date_end = "2012-12-30"
  description = """
As a scientific assistant I was responsible for deploying a naive-Bayes model for [genotyping HBV](http://hbv.geno2pheno.org) using PHP.
"""


[[experience]]
  title = "Teaching Assistant"
  company = "Saarland University"
  company_url = "http://www.uni-saarland.de"
  location = "Saarbrücken"
  date_start = "2011-04-01"
  date_end = "2011-07-30"
  description = """
As a teaching assistant for the lecture *Software  Tools  for  Bioinformatics*, I assisted during the tutorials where we taught students how to use current bioinformatic tools (e.g. Copasi and Cytoscape) and databases (e.g. NCBI and UniProt).
"""

[[experience]]
  title = "Scientific Assistant"
  company = "Max Planck Institute for Informatics"
  company_url = "http://www.mpi-inf.mpg.de"
  location = "Saarbrücken"
  date_start = "2011-03-01"
  date_end = "2011-06-30"
  description = """
In my role as a scientific assistant, I was responsible for documenting the [GISAID EpiFlu database ](https://www.gisaid.org/) using HTML resources.
"""

[[experience]]
  title = "Scientific Assistant"
  company = "Max Planck Institute for Informatics"
  company_url = "http://www.mpi-inf.mpg.de"
  location = "Saarbrücken"
  date_start = "2010-04-01"
  date_end = "2011-01-30"
  description = """
In my role as a scientific assistant, I was responsible for creating a summary of the Bioinformatics 2 lecture. This involved transcribing audios from the lectures, researching bioinformatic methods, and creating a Latex document.
"""
+++
