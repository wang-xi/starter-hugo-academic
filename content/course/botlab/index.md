---
title: ROB 550 (Robotic System Lab) - BotLab
summary: Mobile robot control, SLAM and path planning
tags:
date: "2021-11-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
# - icon: video
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: https://youtu.be/hhkvsWn7VrM

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
In this project, a differential-drive mobile robot "MBot" is assembled. A motion controller is designed by incorporating odometry readings in order to drive the MBot through different desired positions. To minimize the effects of error propagation on odometry readings, the motion controller in conjunction with a SLAM algorithm provides a more accurate localization of the robot. Using this understanding of the environment, an A* path planning algorithm is programmed to enable the MBot to autonomously navigate.

Robot assembly:
![Assembly Process](assembly.png)

Mapping:
![Mapping](mapping.png)

SLAM:
{{<youtube hhkvsWn7VrM>}}

{{<youtube NPI0uSU-q0k>}}


Exploration:
{{<youtube ZYu_5Biz91s>}}