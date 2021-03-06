---
# Documentation: https://wowchemy.com/docs/managing-content/

title: (Short) Object Removal Attacks on LiDAR-based 3D Object Detectors
subtitle: ''
summary: ''
authors:
- Zhongyuan Hau
- Kenneth T. Ko
- Soteris Demetriou
- Emil C. Lupu
tags: []
categories: []
date: '2021-02-01'
lastmod: 2021-03-06T19:32:01Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-03-06T19:32:01.391280Z'
publication_types:
- '1'
abstract: LiDARs play a critical role in Autonomous Vehicles’ (AVs) perception and
  their safe operations. Recent works have demonstrated that it is possible to spoof
  LiDAR return signals to elicit fake objects. In this work we demonstrate how the
  same physical capabilities can be used to mount a new, even more dangerous class
  of attacks, namely Object Removal Attacks (ORAs). ORAs aim to force 3D object detectors
  to fail. We leverage the default setting of LiDARs that record a single return signal
  per direction to perturb point clouds in the region of interest (RoI) of 3D objects.
  By injecting illegitimate points behind the target object, we effectively shift
  points away from the target objects’ RoIs. Our initial results using a simple random
  point selection strategy show that the attack is effective in degrading the performance
  of commonly used 3D object detection models.
publication: '*Third International Workshop on Automotive and Autonomous Vehicle Security
  (AutoSec) - co-located with NDSS*'
url_pdf: https://www.ndss-symposium.org/ndss-paper/auto-draft-112/
---
