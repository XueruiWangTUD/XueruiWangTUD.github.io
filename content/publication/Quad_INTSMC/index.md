---
title: "Quadrotor fault-tolerant incremental nonsingular terminal sliding mode control"
authors:
- Xuerui Wang
- Sihao Sun
- Erik-Jan van Kampen
date: "2019-10-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Aerospace Science and Technology, 2019, Vol 95*"
publication_short: In *AST*

abstract: ﻿This paper proposes incremental nonsingular terminal sliding mode control for a class of multi-input and multi-output nonlinear systems considering model uncertainties, external disturbances, and sudden actuator faults. This method is free from singularity because it does not involve any negative fractional power. The convergence time in both reaching and sliding phases are proved to be finite. Moreover, by fully exploiting sensor measurements, the proposed incremental control method simultaneously reduces model dependency and the uncertainty remaining in the closed-loop system. The reduction of model dependency simplifies the implementation process and reduces the computational load, while the reduction of uncertainty decreases the minimum possible sliding mode control gains, which is beneficial to chattering reduction. These merits are verified by a quadrotor trajectory tracking problem. Simulation results demonstrate that the proposed method has better robustness against model uncertainties, gusts, and actuator faults than the model-based nonsingular terminal sliding mode control in the literature.
# Summary. An optional shortened abstract.
summary: This paper proposes incremental nonsingular terminal sliding mode control for a class of multi-input and multi-output nonlinear systems considering model uncertainties, external disturbances, and sudden actuator faults. The proposed method is applied to a quadrotor fault-tolerant control problem. ﻿
tags:
# - Source Themes
featured: false

# links:
# - name: IEEE Spectrum
#   url: https://spectrum.ieee.org/automaton/robotics/drones/quadrotor-maintains-high-speed-flight-with-just-three-rotors
url_pdf: https://doi.org/10.1016/j.ast.2019.105514
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
# url_video: 'https://www.youtube.com/watch?v=ScYDOqFGOhk'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "3D trajectory tracking in the presence of uncertainties, disturbances, and successive actuator faults."
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

