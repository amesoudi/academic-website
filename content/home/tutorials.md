+++
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Tutorials"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  #gradient_start = "DarkGreen"
  #gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  #text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  #padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

#### Simulation models of cultural evolution in R

This tutorial shows how to create very simple simulation or agent-based models of cultural evolution in R. It uses the RStudio notebook or RMarkdown (.Rmd) format, allowing you to execute code as you read the explanatory text. Each model is contained in a separate RMarkdown file which you can open in RStudio. Currently these are:

* Model 1: Unbiased transmission
* Model 2: Unbiased and biased mutation
* Model 3: Biased transmission (direct/content bias)
* Model 4: Biased transmission (indirect bias)
* Model 5: Biased transmission (conformist bias)
* Model 6: Vertical and horizontal transmission
* Model 7: Migration
* Model 8: Blending inheritance
* Model 9: Demography and cultural gain/loss
* Model 10: Polarization
* Model 11: Cultural group selection
* Model 12: Historical dynamics
* Model 13: Social contagion
* Model 14: Social networks
* Model 15: Opinion formation
* Model 16: Bayesian iterated learning
* Model 17: Reinforcement learning
* Model 18: Evolution of social learning
* Model 19: Evolution of social learning strategies

The tutorial is freely available at https://github.com/amesoudi/cultural_evolution_ABM_tutorial

An online version which contains the compiled models with outputs can be found at https://bookdown.org/amesoudi/ABMtutorial_bookdown/
