+++
# Date this page was created.
date = 2017-09-27

# Project title.
title = "Belief Propagation and Community Detection"
author = "Krishna Bathina and Filippo Radicchi"

# Project summary to display on homepage.
summary = "A new method of community detection that uses a message passing algorithm across pairs of nodes."

# Optional image to display on homepage (relative to `static/img/` folder).
# image_preview = "community_detection.png"

# Tags: can be used for filtering projects.
tags = ["belief propagation", "community detection", "network science"]

# Optional external URL for project (replaces project detail page).
# external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = 
#caption = "My caption :smile:"

+++

Belief propagation is a message passing algorithm applied over a network. The algorithm iteratively passes messages along the edges in order to calculate the marginal distribution of unobserved nodes. [Filippo et al.](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.97.022316) used this idea in order to detect communities in networks by passing edge status as messages. 

We introduce an computationally less expensive approximation and test it on various graphs including GN, LFR, and real graphs. We showed the approximation worked comparably to many popular methods and even outperformed with some graphs with metadata.

Currently under reivew at Applied Network Science.