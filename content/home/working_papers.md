+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Working Papers"
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


### Controlling for discrete unmeasured confounding in nonlinear causal models
*with [Frederick Eberhardt](http://www.its.caltech.edu/~fehardt/), [Michel Besserve](https://michelbesserve.com/)*

*Abstract:* Unmeasured confounding is a major challenge for identifying causal relationships from non-experimental data. Here, we propose a method that can accommodate unmeasured discrete confounding. Extending recent identifiability results in deep latent variable models, we show theoretically that confounding can be detected and corrected under the assumption that the observed data is a piecewise affine transformation of a latent Gaussian mixture model and that the identity of the mixture components is confounded. We provide a flow-based algorithm to estimate this model and perform deconfounding. Experimental results on synthetic and real-world data provide support for the effectiveness of our approach. 

[preprint available here](https://www.dropbox.com/scl/fi/vhs568a1k957ehupdeoar/BurauelEberhardtBesserve_DiscreteConfounding_preprint.pdf?rlkey=82iilf8o08eo8kp31a2unh22w&dl=0)



*******************

### Data-driven definitions of macro-economic concepts: causal representation learning applied to economic complexity
*with [Frederick Eberhardt](http://www.its.caltech.edu/~fehardt/)*

Hidalgo and Hausmann (H&H) developed the [Economic Complexity Index (ECI)](https://www.pnas.org/doi/full/10.1073/pnas.0900943106) as an aggregate measure of the diversity of the productive capabilities of a country. Based on the data from the Atlas of Economic Complexity, ECI is used to predict an economy's long-run growth performance. We make three points: (1) Far simpler data-driven models achieve similar or better in- and out-of-sample predictive accuracy, while grouping economies differently than ECI does. (2) These simple models also generalize to predictions of inequality, with similar predictive accuracy as ECI. (3) To the extent that ECI should be used to underpin policy advice, it fails to distinguish between the cause of growth and the gradient of the cause of growth. We provide an analysis using simple data-driven techniques that could provide the basis for policy recommendations. Overall, our analysis calls into question the the standards by which ECI is considered to be a genuine macro economic quantity, and illustrates a framework that could be used to identify and evaluate data-driven macro economic quantities. 

[preprint available here](https://www.dropbox.com/scl/fi/1apt6nwnl24tujdz60j5o/complexity.pdf?rlkey=ntzqnyds8t6jpxnybd1hmxpv1&st=fq1plu35&dl=0)

*******************

### Testability of Reverse Causality Without Exogenous Variation
*with [Christoph Breunig](https://christophbreunig.wordpress.com/)*, submitted to [The Econometrics Journal](https://academic.oup.com/ectj)

*Abstract:* This paper shows that testability of reverse causality is possible even in the absence of exogenous variation, such as in the form of instrumental variables. Instead of relying on exogenous variation, we achieve testability by imposing relatively weak model restrictions and exploiting that a dependence of residual and purported cause is informative about the causal direction. Our main assumption is that the true functional relationship is nonlinear and that error terms are additively separable. We extend previous results by incorporating control variables and allowing heteroskedastic errors. We build on reproducing kernel Hilbert space (RKHS) embeddings of probability distributions to test conditional independence and demonstrate the efficacy in detecting the causal direction in both Monte Carlo simulations and an application to German survey data.

[link to arxiv version](https://arxiv.org/pdf/2107.05936.pdf)

*******************

### The German Minimum Wage and Wage Growth: Heterogeneous Treatment Effects Using Causal Forests
*with [Carsten Schröder](https://www.diw.de/de/diw_01.c.439337.de/personen/schroeder__carsten.html)*

*Abstract:* Previous research suggests that minimum wages induce heterogeneous treatment effects on wages across different groups of employees. This research usually defines groups ex ante. We analyze to what extent effect heterogeneities can be discerned in a data-driven manner by adapting the generalized random forest implementation of Athey et al (2019) in a difference-in-differences setting. Such a data-driven methodology allows detecting the potentially spurious nature of heterogeneities found in subgroups chosen ex-ante. The 2015 introduction of a minimum wage in Germany is the institutional background, with data of the Socio-economic Panel serving as our empirical basis. Our analysis not only reveals considerable treatment heterogeneities, it also shows that previously documented effect heterogeneities can be explained by interactions of other covariates. 

[link to SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3344981)
