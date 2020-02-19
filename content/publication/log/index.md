+++
title = "MobiLogLeak: A Preliminary Study on Data Leakage Caused by Poor Logging Practices"
date = 2020-01-18T19:25:24-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Rui Zhou","Mohammad Hamdaqa", "Haipeng Cai", "Abdelwahab Hamou-Lhadj"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "2020 IEEE 27th International Conference on Software Analysis, Evolution and Reengineering"
publication_short = "SANER"

# Abstract and optional shortened version.
abstract = "Logging is an essential software practice that is used by developers to debug, diagnose and audit software systems. Despite the advantages of logging, poor logging practices can potentially leak sensitive data. The problem of data leakage is more severe in applications that run on mobile devices, since these devices carry sensitive identification information ranging from physical device identifiers (e.g., IMEI MAC address) to communications network identifiers (e.g., SIM, IP, Bluetooth ID), and application-specific identifiers related to the location and the users’ accounts. This preliminary study explores the impact of logging practices on data leakage of such sensitive information. Particularly, we want to investigate whether log-related statements inserted into an application code could lead to data leakage. While studying logging practices in mobile applications is an active research area, to our knowledge, this is the first study that explores the interplay between logging and security in the context of mobile applications for Android. We propose an approach called MobiLogLeak, an approach that identifies log statements in deployed apps that leak sensitive data. MobiLogLeak relies on taint flow analysis. Among 5,000 Android apps that we studied, we found that 200 apps leak sensitive data through logging."
abstract_short = "We propose an approach called MobiLogLeak, an approach that identifies log statements in deployed apps that leak sensitive data. MobiLogLeak relies on taint flow analysis. "

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://github.com/r-zh/blog/blob/master/content/publication/log/saner2020_final.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
