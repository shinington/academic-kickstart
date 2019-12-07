---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adversarial Regression with Multiple Learners"
authors: 
 - Liang Tong*
 - Sixie Yu*
 - Scott Alfeld
 - Yevgeniy Vorobeychik
date: 2018-07-15T20:24:56-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-06T20:24:56-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 35th International Conference on Machine Learning (ICML'18)*
publication_short: In *ICML'18*

abstract: Despite the considerable success enjoyed by machine learning techniques in practice, numerous studies demonstrated that many approaches are vulnerable to attacks. An important class of such attacks involves adversaries changing features at test time to cause incorrect predictions. Previous investigations of this problem pit a single learner against an adversary. However, in many situations an adversary’s decision is aimed at a collection of learners, rather than specifically targeted at each independently. We study the problem of adversarial linear regression with multiple learners. We approximate the resulting game by exhibiting an upper bound on learner loss functions, and show that the resulting game has a unique symmetric equilibrium. We present an algorithm for computing this equilibrium, and show through extensive experiments that equilibrium models are significantly more robust than conventional regularized linear regression.

# Summary. An optional shortened abstract.
summary: In *Proceedings of the 35th International Conference on Machine Learning (ICML'18)*

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/marsplus/Adversarial-Regression-with-Multiple-Learners
url_dataset:
url_poster: tong2018poster.pdf
url_project:
url_slides: http://sixie-yu.org/assets/slides/icml18.pdf
url_source:
url_video: https://vimeo.com/287807252

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- robust-multiagent-ml

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
