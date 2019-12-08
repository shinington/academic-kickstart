+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Research"
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
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Adversarial Machine Learning"
    tag = "Adversarial Machine Learning"

  [[content.filter_button]]
    name = "Adversarial Reinforcement Learning"
    tag = "Adversarial Reinforcement Learning"

  [[content.filter_button]]
    name = "Malware Detection"
    tag = "Malware Detection"

  [[content.filter_button]]
    name = "Alert Prioritization"
    tag = "Alert Prioritization"

  [[content.filter_button]]
    name = "Mobile Cloud Computing"
    tag = "Mobile Cloud Computing"


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

Machine learning (ML) has been widely used in security applications such as anomaly and malware detection. However, several security issues emerge from ML-based detection systems. First, ML models are often susceptible to evasion attacks, in which an adversary makes changes to the input (such as malware) to avoid being detected. Second, using detection systems in practice is in dealing with an overwhelming number of alerts that are triggered by normal behavior (the so-called false positives), obscuring alerts resulting from actual malicious activities. Third, adversaries can target a broad array of ML-based detection systems to maximize impact rather than specifically targeted at each independently, but this is generally ignored by individual ML system designers. My research addresses these challenges by designing robust features, robust ML models, robust alert prioritization, and robust ML with multiple agents. Through continuous research in this field, I envision robust end-to-end and multi-agent ML-based detection systems.

