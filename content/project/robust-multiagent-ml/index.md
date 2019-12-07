---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust ML with Multiple Learners"
summary: " "
authors: []
tags: 
 - Adversarial Machine Learning
categories: []
date: 2018-02-08T13:31:52-06:00

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

Increasing use of machine learning in adversarial settings has motivated a series of efforts investigating the extent to which learning approaches can be subverted by malicious parties. An important class of such attacks involves adversaries changing their behaviors, or features of the environment, to effect an incorrect prediction. Most previous efforts study this problem as an interaction between a single learner and a single attacker. However, in reality attackers often target a broad array of potential victim organizations. For example, they craft generic spam templates and generic malware, and then disseminate these widely to maximize impact. The resulting ecology of attack targets reflects not a single learner, but many such learners, all making autonomous decisions about how to detect malicious content, although these decisions often rely on similar training datasets.

In this project, we study the linear regression problem in an adversarial setting where the adversary's decision is aimed at a collection of learners, rather than specifically targeted at each independently. We model the resulting game as an interaction between multiple learners, who simultaneously learn linear regression models, and an attacker, who observes the learned models and modifies the original feature vectors at test time to induce incorrect predictions. We propose a simple but effective approach to solve the game, and theoretically prove the solution's uniqueness and robustness. Our approach is applied to PDF malware scoring and house price prediction, which demonstrate it to be much more robust to attacks than standard regularization approaches.
