---
title: ROB 550 (Robotic System Lab) - ArmLab
summary: Block pick-and-place with robot arm
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
url_video: https://youtu.be/wyz150DDCcE

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
In this project, a robotic arm arrange blocks of different sizes, colors, and placements,
into a desired arrangement completely autonomously. Analytical inverse kinematics is used to determine the appropriate waypoints for our desired end-effector position. A PID controller is developed to navigate each joint to desired waypoints. An overhead Intel RealSense LiDAR Camera is utilized to identify blocks on the board. Homogeneous transformations are used to relate pixel and depth coordinates to real-world coordinates. For reliability, the extrinsic matrix is calibrated using four apriltags with known positions.

The project results are demonstrated through four competitions.

Competition 1: Sort large blocks to the right and small blocks to the left.
{{<youtube JjvOFVKZ2dA>}}

Competition 2: Stack blocks into stacks with 3 block in each stack.
{{<youtube pSod5o089tE>}}

Competition 3: Place large and small blocks into two lines in rainbow color order. 
{{<youtube wyz150DDCcE>}}

Competition 4: Place large and small blocks into two stacks in rainbow color order. 
{{<youtube w4TPFx0ucxU>}}