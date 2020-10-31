---
title: "Quadrotor fault tolerant incremental sliding mode control driven by sliding mode disturbance observers"
authors:
- Xuerui Wang
- Sihao Sun
- Erik-Jan van Kampen
- Qiping Chu
date: "2019-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Aerospace Science and Technology
, 87*"
publication_short: In *AST*

abstract: This paper proposes an Incremental Sliding Mode Control driven by Sliding Mode Disturbance Observers (INDI-SMC/SMDO), with application to a quadrotor fault tolerant control problem. By designing the SMC/SMDO based on the control structure of the sensor-based Incremental Nonlinear Dynamic Inversion (INDI), instead of the model-based Nonlinear Dynamic Inversion (NDI) in the literature, the model dependency of the controller and the uncertainties in the closed-loop system are simultaneously reduced. This allows INDI-SMC/SMDO to passively resist a wider variety of faults and external disturbances using continuous control inputs with lower control and observer gains. When applied to a quadrotor, both numerical simulations and real-world flight tests demonstrate that INDI based SMC/SMDO has better performance and robustness over NDI based SMC/SMDO, in the presence of model uncertainties, wind disturbances, and sudden actuator faults. Moreover, the implementation process is simplified because of the reduced model dependency and smaller uncertainty variations of INDI-SMC/SMDO. Therefore, the proposed control method can be easily implemented to improve the performance and survivability of quadrotors in real life.

# Summary. An optional shortened abstract.
summary: This work introduces a novel control method named Incremental Sliding Mode Control, which greatly reduces model dependency and improves the robustness against uncertainties. The algorithm has been validated in a quadrotor fault-tolerant control problem in real flight.

tags:
# - Source Themes
featured: false

# links:
# - name: IEEE Spectrum
#   url: https://spectrum.ieee.org/automaton/robotics/drones/quadrotor-maintains-high-speed-flight-with-just-three-rotors
url_pdf: https://www.researchgate.net/publication/331584654_Quadrotor_Fault_Tolerant_Incremental_Sliding_Mode_Control_driven_by_Sliding_Mode_Disturbance_Observers
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
# url_video: 'https://www.youtube.com/watch?v=ScYDOqFGOhk'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "The damaged quadrotor flies in the wind tunnel"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- AircraftFTC

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

