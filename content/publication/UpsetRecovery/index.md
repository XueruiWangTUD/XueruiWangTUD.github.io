---
title: "Upset Recovery Control for Quadrotors Subjected to a Complete Rotor Failure from Large Initial Disturbances"
authors:
- admin
- Matthias Beart
- Bram Strack van Schijndel
- Coen de Visser
date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2020 IEEE International Conference on Robotics and Automation"
publication_short: In *ICRA 2020*

abstract: This study has developed a fault-tolerant controller that is able to recover a quadrotor from arbitrary initial orientations and angular velocities, despite the complete failure of a rotor. This cascaded control method includes a position/altitude controller, an almost-global convergence attitude controller, and a control allocation method based on quadratic programming. As a major novelty, a constraint of undesirable angular velocity is derived and fused into the control allocator, which significantly improves the recovery performance. For validation, we have conducted a set of Monte-Carlo simulation to test the reliability of the proposed method of recovering the quadrotor from arbitrary initial attitude/rate conditions. In addition, real-life flight tests have been performed. The results demonstrate that the post-failure quadrotor can recover after being casually tossed into the air.

# Summary. An optional shortened abstract.
summary: We introduce a flight controller that can recover a quadrotor with one rotor complete off from arbitrary initial orientations and body rates.

tags:
- Source Themes
featured: true

links:
- name: ICRA online presentation
  url: https://youtu.be/-5cSnRNPCrg
- name: Master Thesis
  url: https://repository.tudelft.nl/islandora/object/uuid%3A4e1011c7-2db9-4dfe-a910-f2843414b960
url_pdf: https://arxiv.org/pdf/2002.09425.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://www.youtube.com/watch?v=PJ5U3ZAm8NM&t=31s


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Toss and recover a quadrotor with only three propellers."
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- QuadrotorFTC

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

