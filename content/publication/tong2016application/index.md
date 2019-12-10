---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Application-Aware Traffic Scheduling for Workload Offloading in Mobile Clouds"
authors: 
 - admin
 - Wei Gao
date: 2016-04-06T21:04:34-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-06T21:04:34-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 35th IEEE Conference on Computer Communications (INFOCOM'16)*
publication_short: In *INFOCOM*

abstract: Mobile Cloud Computing (MCC) bridges the gap between limited capabilities of mobile devices and the increasing complexity of mobile applications, by offloading the computational workloads from local devices to the cloud. Current research supports workload offloading through appropriate application partitioning and remote method execution, but generally ignores the impact of wireless network characteristics on such offloading. Wireless data transmissions incurred by remote method execution consume a large amount of additional energy during transmission intervals when the network interface stays in the high-power state, and deferring these transmissions increases the response delay of mobile applications. In this paper, we adaptively balance the tradeoff between energy efficiency and responsiveness of mobile applications by developing application-aware wireless transmission scheduling algorithms. We take both causality and run-time dynamics of application method executions into account when deferring wireless transmissions, so as to minimize the wireless energy cost and satisfy the application delay constraint with respect to the practical system contexts. Systematic evaluations show that our scheme significantly improves the energy efficiency of workload offloading over realistic smartphone applications.

# Summary. An optional shortened abstract.
summary: In *Proceedings of the 35th IEEE Conference on Computer Communications (INFOCOM'16)*

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
url_code:
url_dataset:
url_poster:
url_project:
url_slides: infocom16-mobilecloud.pptx
url_source:
url_video:

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
- mobile-edge-cloud

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
