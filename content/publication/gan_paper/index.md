---
title: "An Empirical Evaluation of DP GANs for Social Science"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Marcel Neunhoeffer
- Christian Arnold
- Sebastian Sternberg

# Author notes (optional)

date: "2019-06-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Working Paper
publication_short: Working Paper

abstract: Political scientists pervasively use data that contains sensitive information -- e.g. micro-level data about individuals. However, researchers face a dilemma while data has to be publicly available to make research reproducible, information about individuals needs to be protected. Synthetic copies of original data can address this concern, because ideally they contain all relevant statistical characteristics without disclosing private information. But generating synthetic data that captures--eventually undiscovered--statistical relationships is challenging. Moreover, it so far remains unsolved to fully control the amount of information disclosed during this process. To that end differentially private generative adversarial networks (DP-GANs) have been proposed in the (computer science) literature. We experimentally evaluate the trade-off between data utility and privacy protection in a simulation study by looking at evaluation metrics that are important for social scientists, specifically in terms of regression coefficients, marginal distributions and correlation structures. Our findings suggest that on average, higher levels of provided privacy negatively affects the synthetic data quality. We hope to encourage inter-disciplinary work between computer scientists and social scientists to develop more powerful DP-GANs in the future.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'pdf/An_Empirical_Evaluation_of_DP_GANs_for_Social_Science.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example

---