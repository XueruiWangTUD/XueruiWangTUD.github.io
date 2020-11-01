---
title: Quadrotor Fault Tolerant Control
summary: In this project, we design fault-tolerant control algorithms for quadrotors with complete loss of one or more rotors in high-speed flights.
tags:
- Quadrotor Fault Tolerant Control
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A quadrotor flies with 3 propellers.
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

As the most commonly used and simplest multi-rotor drones, quadrotors are
especially vulnerable to rotor failures because they lack rotor redundancy. This project aims at introducing novel flight control methods to mitigate the consequence of in-flight motor failures, which rarely happens but is still a big safety threat after large scale deployment of drones in the future.

To be specific, the project leverages incremental nonlinear dynamic inversion (INDI) control method, to stabilize and control a quadrotor with failure of a [**single rotor**](/publication/highspeedral/) or [**two opposing rotors**](/publication/incrementalnonlinear/), under significant aerodynamic disturbances. These strong aerodynamic effects are dominant in high-speed flight, or windy conditions. Thanks to the robustness of the INDI controller, the damaged quadrotor maintains controllable in spite of these aeordynamic disturbances.

We have validated the proposed controllers in a large scale wind tunnel, named [**Open Jet Facility**](https://www.tudelft.nl/lr/organisatie/afdelingen/aerodynamics-wind-energy-flight-performance-and-propulsion/facilities/low-speed-wind-tunnels/open-jet-facility/) at TU Delft. Despite a complete loss of one or two propellers, the tested quadrotor can maintain high-speed flight. In addition to validating the controller, these wind tunnel flight tests have produced valuable data for identifying [**aerodynamic models**](/project/quadrotormodeling) of a quadrotor, in both nominal and damaged conditions.

Another focus of the research aims at recovering the damaged quadrotor after motor failure. When a motor failure is detected, a quadrotor might have been entered a detrimental flight condition, such as an upside-down orientation, where the drone can hardly recover to stable flights using the state-of-art methods.
Therefore, we have developed an [**upset recovery controller**](/publication/upsetrecovery/), using a novel control allocation approach.