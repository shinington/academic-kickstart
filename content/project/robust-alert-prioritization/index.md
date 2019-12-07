---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Alert Prioritization"
summary: " "
authors: []
tags: 
 - Adversarial Reinforcement Learning
 - Alert Prioritization
#categories: []
date: 2019-12-06T13:30:08-06:00

# Optional external URL for project (replaces project detail page).
#external_link: ""

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

Detection of malicious behavior is a fundamental problem in security. One of the major challenges in using detection systems in practice is in dealing with an overwhelming number of alerts that are triggered by normal behavior (the so-called false positives), obscuring alerts resulting from actual malicious activity. While numerous methods for reducing the scope of this issue have been proposed, ultimately one must still decide how to prioritize which alerts to investigate, and most existing prioritization methods are heuristic, for example, based on suspiciousness or priority scores. However, any policy that deterministically orders alerts potentially opens the door for determined attackers who can simply choose attacks that are rarely investigated, thereby evading detection.

In this project, we study the problem of deciding which of a large number of alerts to choose for further investigation where only a small subset can ever be closely examined—often a necessary step in the detection pipeline. We propose a novel model and principled computational approach for robust alert prioritization. We model the problem of robust alert prioritization as a game in which the defender chooses a stochastic policy for selecting alerts as a function of observable state, while the attacker chooses which attacks to execute with full knowledge of the system state. To tackle the computational complexity of solving this game to obtain a dynamic stochastic alert prioritization policy, we propose an *adversarial reinforcement learning* framework. In this framework, we use neural reinforcement learning to compute best response policies for both the defender and the adversary to an arbitrary stochastic policy of the other. We then use these in a *double-oracle* framework to obtain an approximate equilibrium of the game, which in turn yields a robust stochastic policy for the defender.

We evaluate our approach experimentally in two application domains: *network intrusion detection*, where we use the Suricata open-source network intrusion-detection system (NIDS) with a network IDS dataset, and *fraud detection*, with a detector learned from data using machine learning. In both settings, we show that our approach is significantly more effective than alternatives with respect to our threat model. Furthermore, we demonstrate that our approach remains highly effective, and better than baseline alternatives in nearly all cases, even when certain assumptions of our threat model are violated.


