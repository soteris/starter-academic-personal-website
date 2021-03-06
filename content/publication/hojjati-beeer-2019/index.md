---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'BEEER: distributed record and replay for medical devices in hospital operating
  rooms'
subtitle: ''
summary: ''
authors:
- Avesta Hojjati
- Yunhui Long
- Soteris Demetriou
- Carl A. Gunter
tags: []
categories: []
date: '2019-01-01'
lastmod: 2021-03-06T18:52:31Z
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
publishDate: '2021-03-06T18:52:31.777489Z'
publication_types:
- '1'
abstract: Medical devices in hospital operating rooms are getting increasingly interconnected.
  This enables them to download instructions and report results with less risk of
  error compared to traditional manual techniques. However, many of these devices
  are safety critical. Thus, any risks from cyber-attacks can be extremely high. This
  paper describes BEEER, a distributed record and replay framework suitable for environments
  where more than one safety critical device is in simultaneous use. A prominent example
  is a hospital operating room where a number of networked devices work together.
  In such scenarios, a key step to forensically analyze an incident is understanding
  the causality of events produced by devices. BEEER orders events during recording
  by leveraging the fact that it takes significantly more time for a drug’s effects
  to come to prominence on a patient compared to device-to-device communication on
  a local network. During replay, BEEER uses a newly developed token mechanism to
  coordinate execution of the events. We implemented and evaluated a prototype of
  BEEER. We found that synchronization for short medical operations can be achieved
  using Network Time Protocol (NTP). For longer operations we designed and developed
  a new event ordering protocol (projection protocol) based on vector timestamps.
  BEEER’s replay mechanism is efficient and therefore suitable for forensics analyses
  in practice.
publication: "*Proceedings of the 6th Annual Symposium on Hot Topics in the Science\
  \ of Security  - HotSoS '19*"
url_pdf: http://dl.acm.org/citation.cfm?doid=3314058.3314061
doi: 10.1145/3314058.3314061
---
