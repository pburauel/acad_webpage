+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Job Market Paper"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "projects"
  
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


### Evaluating Instrument Validity using the Principle of Independent Mechanisms

published at [Journal of Machine Learning Research](https://jmlr.org/papers/v24/20-1287.html)

*Abstract:* The validity of instrumental variables to estimate causal effects is typically justified narratively and often remains controversial. Critical assumptions are difficult to evaluate since they involve unobserved variables. Building on Janzing and Schölkopf’s (2018) method to quantify a degree of confounding in multivariate linear models, we develop a test that evaluates instrument validity without relying on Balke and Pearl’s (1997) inequality constraints. Instead, our approach is based on the Principle of Independent Mechanisms, which states that causal models have a modular structure. Monte Carlo studies show a high accuracy of the procedure. We apply our method to two empirical studies: first, we can corroborate the narrative justification given by Card (1995) for the validity of college proximity as an instrument for educational attainment to estimate financial returns to education. Second, we cannot reject the validity of past savings rates as an instrument for economic development to estimate its causal effect on democracy (Acemoglu et al., 2008). 



*******************
