---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mobile Edge Cloud"
summary: " "
authors: []
tags: 
 - Mobile Cloud Computing
categories: []
date: 2015-07-31T13:32:42-06:00

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

One of the most important challenges in mobile computing is to address the contradiction between the increasing complexity of mobile applications and the limited local capabilities of mobile devices. A viable solution is to leverage cloud computing and execute mobile applications remotely, but this raises two challenges: First, modern cloud computing services are solely hosted by data centers and incapable of efficiently executing mobile applications due to long network transmission latency and significant overhead for global VM provisioning and management. Recent research efforts reduce network latency accessing data centers by deploying an intermediate cloud layer, so-called cloudlets, at the network edge, but cannot handle the peak load exceeding the capacity of the cloudlets. Second,  data transmission between mobile devices and the remote cloud through cellular networks is expensive. Current research supports workload offloading through appropriate application partitioning and remote method execution, but generally ignores the interdependency between wireless transmissions and mobile application executions. This could seriously degrade energy efficiency of workload offloading. 

To address the first challenge, we propose to deploy cloud servers at the network edge and design the edge cloud as a tree hierarchy of geo-distributed servers, so as to efficiently utilize the cloud resources to serve the peak loads from mobile users. The hierarchical architecture of edge cloud enables aggregation of the peak loads across different tiers of cloud servers to maximize the amount of mobile workload being served. To ensure efficient utilization of cloud resources, we further propose a workload placement algorithm that decides which edge cloud servers mobile programs are placed on and how much computational capacity is provisioned to execute each program. 

To address the second challenge,  we adaptively balance the tradeoff between energy efficiency and responsiveness of mobile applications. Being different from existing work which regardlessly defers wireless transmissions into groups, we take both causality and run-time dynamics of application method executions into account when deferring wireless transmissions, so as to minimize the wireless energy cost while satisfying the specified application
delay constraints.

