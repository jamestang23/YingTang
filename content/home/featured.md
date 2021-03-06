+++
# A Featured Publications section created with the Featured Content widget.
# This section displays publications from `content/publication/` which have
# `featured = true` in their front matter.

widget = "featured"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "Research Highlights"
subtitle = ""

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Show a "See all pages" link underneath the featured content?
  link_to_archive = false

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 1
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

* **Nonequilibrium quantum thermodynamics:**

As a remarkable advance in nonequilibrium thermodynamics during the last 20 years, Jarzynski equality connects free energy changes to nonequilibrium work fluctuations. We found that the free energy change through the Jarzynski equality is independent of magnetic field in the classical regime [[1]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.91.042108), but can be amplified by magnetic field in driven quantum system [[2]](https://www.nature.com/articles/s42005-020-00509-9).
  

* **Information theory:**

Inferring mutual information from time series data remained challenging as the possible trajectory configurations increases exponentially with the number of time points. We develop a [computational framework](https://sites.google.com/view/dmipackage/home) to quantify the dynamical mutual information of intracellular signaling process [[3]](https://www.nature.com/articles/s41467-021-21562-0).

* **Stochastic process without detailed balance:**

Stochastic transitions are ubiquitous in nature. Based on path integral approach [[4]](https://aip.scitation.org/doi/abs/10.1063/1.4890968), we develop a scalable numerical approach to calculate transition rates for a class of stochastic dynamics [[5]](https://www.nature.com/articles/s41598-017-15889-2). The computational cost is robust to varying noise intensity, beyond small noise limit. The efficient computations on transition rates enable a broader use of stochastic modeling in complex dynamics, such as cell state transitions [[6]](https://www.nature.com/articles/nmeth.4402.pdf?origin=ppub).


