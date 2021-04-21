+++
# Project title.
title = "Single-cell integration of inflammatory diseases and COVID-19 from diseased tissues"

# Date this page was created.
date = 2021-04-20T00:00:00

# Project summary to display on homepage.
summary = "Autoimmune, cytokine, macrophage, single-cell integration, COVID-19"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cross-disease tissue integration"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# # Slides (optional).
# #   Associate this project with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references 
# #   `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides = "example-slides"
# 
# # Links (optional).
# url_pdf = ""
# url_slides = ""
# url_video = ""
# url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/FanZhang_Jessie"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "headers/stm_macro.png"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
  
[header]
image = "headers/stm_macro.png"

+++

*Motivation*: Understanding the immune cell states shared between COVID-19 and other inflammatory diseases with established therapies may help nominate immunomodulatory therapies.

*Build an immune cell reference* consisting of >300,000 single-cell transcriptomic profiles from COVID-19 affected lungs and tissues from healthy subjects and patients with 5 inflammatory diseases: rheumatoid arthritis (RA), Crohn’s disease (CD), ulcerative colitis (UC), lupus, and interstitial lung disease. We tested the association of shared immune states with severe/inflamed status compared to healthy using mixed-effects modeling.

*Identify a CXCL10+ CCL2+ inflammatory macrophage phenotype* that is shared and strikingly abundant in severe COVID-19 bronchoalveolar lavage samples, inflamed RA synovium, inflamed CD ileum and UC colon. We found this macrophage phenotype is induced upon co-stimulation by IFN-γ and TNF-α collaborating with the Donlin lab.

*A proof of concept*: This reference can be used to query/investigate cells from other inflammatory diseases and their transcriptomic similarities with our reference which incorporates 5 inflammatory diseased tissues and COVID-19 BALF. We provide a [Notebook of example code](https://github.com/immunogenomics/inflamedtissue_covid19_reference/blob/master/code/Map_Sepsis_to_FanImmuneReference_using_Symphony_Notebook.ipynb) to show how to map Sepsis PBMCs (Reyes, et al, Nature Medicine, 2020) to our cross-diseased tissue single-cell reference and identify shared inflammatory structures.

Citation: Zhang, Fan, et al. IFN-γ and TNF-α drive a CXCL10+ CCL2+ macrophage phenotype expanded in severe COVID-19 lungs and inflammatory diseases with tissue inflammation. Genome Medicine, 2021.




