+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  # name = "All"
  # tag = "*"
  
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

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
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++


### What the Degree of Structural Autonomy Can Say about Instrument Validity

*Abstract:* The validity of instrumental variables to estimate causal eﬀects is typically justifed narratively and often remains controversial. Thus, more objective evaluation of instrument validity through data-driven methods is desirable. I build on a method to quantify the degree of confounding in multivariate linear models, which invokes arguments about the autonomy of mechanisms linking cause and eﬀect, and show how it can be used to evaluate instrument validity. Monte Carlo studies show a high accuracy of the procedure. An empirical application shows its feasibility in practice. 

\[[link to SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3344981)\]

*******************

### A test for reverse causality without instruments
*with [Christoph Breunig](https://christophbreunig.wordpress.com/)*

*Abstract:* Endogeneity is a central problem in econometric models which potentially invalidates estimates of causal eﬀects. Existing tests of endogeneity often require that a potential solution in the form of instruments is available. In situations in which instruments are not available, a test that does not require them is needed. This paper presents a heteroskedasticity-robust test for reverse causality, as one type of endogeneity, of a single regressor without requiring instruments. The fundamental assumption is that the data generating process can be represented by a regression model with additively separable error term and a nonlinear relation between cause and eﬀect. We move beyond the mean independence assumption and require the error to be independent of the regressor, which allows us to make inference on the causal direction between the variables at hand. We leverage
advances on kernel-based testing of conditional independence of random variables.

\[available upon request\]

*******************

### The German Minimum Wage and Wage Growth: Heterogeneous Treatment Effects Using Causal Forests
*with [Carsten Schröder](https://www.diw.de/de/diw_01.c.439337.de/personen/schroeder__carsten.html)*

*Abstract:* Previous research suggests that minimum wages induce heterogeneous treatment effects on wages across different groups of employees. This research usually defines groups ex ante. We analyze to what extent effect heterogeneities can be discerned in a data-driven manner by adapting the generalized random forest implementation of Athey et al (2019) in a difference-in-differences setting. Such a data-driven methodology allows detecting the potentially spurious nature of heterogeneities found in subgroups chosen ex-ante. The 2015 introduction of a minimum wage in Germany is the institutional background, with data of the Socio-economic Panel serving as our empirical basis. Our analysis not only reveals considerable treatment heterogeneities, it also shows that previously documented effect heterogeneities can be explained by interactions of other covariates. 

\[[link to SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3344981)\]
