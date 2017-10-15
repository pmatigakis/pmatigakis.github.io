+++
# Date this page was created.
date = "2017-10-15"

# Project title.
title = "Huginn"

# Project summary to display on homepage.
summary = "Open source flight simulator"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "huginn.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["simulation"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/huginn-wide.png"
caption = "huginn"

+++

Huginn is a flight simulator designed for software-in-the-loop and hardware-in-the-loop simulations.
The simulator is written in Python using the JSBSim flight dynamics model library.

Huginn can be controlled over a REST API interface. The aircraft's flight data and
controls can be accessed through a REST API interface or as Protocol Buffer encoded
packets over a UDP connection

* Project repository: https://github.com/pmatigakis/Huginn
