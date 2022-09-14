---
title: 'Distributionally Robust Policy Learning with Wasserstein Distance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-10T00:00:00Z'
doi: '10.48550/ARXIV.2205.04637'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv

abstract: The effects of treatments are often heterogeneous, depending on the observable characteristics, and it is necessary to exploit such heterogeneity to devise individualized treatment rules (ITRs). Existing estimation methods of such ITRs assume that the available experimental or observational data are derived from the target population in which the estimated policy is implemented. However, this assumption often fails in practice because of limited useful data. In this case, policymakers must rely on the data generated in the source population, which differs from the target population. Unfortunately, existing estimation methods do not necessarily work as expected in the new setting, and strategies that can achieve a reasonable goal in such a situation are required. This study examines the application of distributionally robust optimization (DRO), which formalizes an ambiguity about the target population and adapts to the worst-case scenario in the set. It is shown that DRO with Wasserstein distance-based characterization of ambiguity provides simple intuitions and a simple estimation method. I then develop an estimator for the distributionally robust ITR and evaluate its theoretical performance. An empirical application shows that the proposed approach outperforms the naive approach in the target population.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2205.04637.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
