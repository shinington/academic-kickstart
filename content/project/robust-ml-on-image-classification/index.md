---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust ML on Image Classification"
summary: " "
authors: []
tags: []
categories: []
date: 2019-08-30T15:52:36-06:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

State-of-the-art effectiveness of deep neural networks has made it the technique of choice in computer vision.  However, there have been a myriad of demonstrations showing that deep neural networks can be easily fooled by carefully perturbing pixels in an image through what have become known as *adversarial example attacks*. In response, a large literature has emerged on defending deep neural networks against adversarial examples, typically either proposing techniques for learning more robust neural network models.

Particularly concerning, however, have been a number of demonstrations that implement adversarial perturbations directly in physical objects that are subsequently captured by a camera, and then fed through the deep neural network classifier. These attacks are called *physical attacks* such that they can be *realizable* in physical world. e.g., the attack which fools face recognition by using adversarially designed eyeglass frames, or the attack which fools
stop sign classification by adding adversarially crafted stickers. Oddly, while considerable attention has
been devoted to defending against adversarial perturbation attacks in the digital space, there are no
effective methods specifically to defend against such physical attacks.

We make several contributions in designing robust ML models on image classification in face of *physical attacks*. First, we conduct case studies on face recognition and traffic sign classification and investigate effectiveness of conventional approaches (e.g., adversarial training that leverages lp attacks, and randomized smoothing) to robust ML against physically realizable attacks. We show that these approaches are largely ineffective in this context. Second, we propose a novel abstract attack model which more directly captures the nature of common physically realizable attacks than the conventional lp-based models, and use adversarial training to obtain neural network models that are robust to the proposed model. We use an extensive experimental evaluation to demonstrate that our proposed approach is far more robust against physical attacks on deep neural networks than adversarial training and randomized smoothing methods that leverage lp-based models. 


