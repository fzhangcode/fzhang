+++
# About widget.
widget = "about"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 5  # Order that this section will appear in.


# List your academic interests.
[interests]
  interests = [
    "Single-cell multi-omics",
    "Bayesian statistics and optimization",
    "Computational immunology",
    "Autoimmune disease"
  ]

# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "PhD in Bioinformatics and Biomedical Engineering"
  institution = "Worcester Polytechnic Institute, MA USA"
  year = 2017
  month = 2

[[education.courses]]
  course = "MS in Bioinformatics"
  institution = "Jilin University, Changchun, China"
  year = 2012

[[education.courses]]
  course = "BS in Computer Science"
  institution = "Jilin University, Chaungchun, China"
  year = 2009

  
# Choose the user profile to display
# This should be the username of a profile in your `content/author/` folder.
# author = "admin"



# About me
I am a Computational Biologist working in [immunogenomics](https://immunogenomics.hms.harvard.edu/) with [Dr. Soumya Raychaudhuri](https://dbmi.hms.harvard.edu/person/faculty/soumya-raychaudhuri) in collaboration with [Dr. Michael Brenner](https://www.hms.harvard.edu/dms/immunology/fac/Brenner.php) at Harvard Medical School, Brigham and Women's Hospital (BWH), and Broad Institute of Harvard and MIT at Boston.
My research interests lie in the application of bioinformatics and statistics to study autoimmune diseases, medicine, and public health.
Recently, I focus on developing accurate and computationally scalable methods to study single-cell transcriptomics and proteomics to discover potential drug targets for rheumatic diseases.
I am also part of the Bioinformatics team of the BWH [10X Single Cell Genomics Core](https://singlecell.bwh.harvard.edu/).


I received my PhD in [bioinformatics and biomedical engineering at WPI](https://www.wpi.edu/academics/departments/biomedical-engineering) where I worked with [Dr. Patrick Flaherty](https://people.math.umass.edu/~flaherty/?_ga=2.161809467.684947861.1552584709-2039651767.1552584709) on Bayesian statistics and machine learning for large-scale genomic data.
I also worked with [Dr. Andrew C. Trapp](http://users.wpi.edu/~atrapp/) on developing global optimization algorithms to solve mixed membership models.


[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
    
  # Background color.
  color = "#BEBADA"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

{{% alert note %}}
Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}).
{{% /alert %}}
