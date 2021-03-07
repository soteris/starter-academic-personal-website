---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Ghost Installer in the Shadow: Security Analysis of App Installation on Android'
subtitle: ''
summary: ''
authors:
- Y. Lee
- T. Li
- N. Zhang
- S. Demetriou
- M. Zha
- X. Wang
- K. Chen
- X. Zhou
- X. Han
- M. Grace
tags:
- '"AIT development"'
- '"Android (operating system)"'
- '"Android ecosystem"'
- '"Androids"'
- '"App installation transaction"'
- '"dubbed ghost installer attack"'
- '"Fasteners"'
- '"GIA"'
- '"Google"'
- '"Humanoid robots"'
- '"Security"'
- '"security analysis"'
- '"security of data"'
- '"security-critical loopholes"'
- '"Smart phones"'
- '"system-level defense"'
- '"Systematics"'
- '"user-app-level"'
categories: []
date: '2017-06-01'
lastmod: 2021-03-06T18:52:32Z
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
projects: [mobile-devices-and-iot-systems-security]
publishDate: '2021-03-06T19:32:02.864803Z'
publication_types:
- '1'
abstract: 'Android allows developers to build apps with app installation functionality
  themselves with minimal restriction and support like any other functionalities.
  Given the critical importance of app installation, the security implications of
  the approach can be significant. This paper reports the first systematic study on
  this issue, focusing on the security guarantees of different steps of the App Installation
  Transaction (AIT). We demonstrate the serious consequences of leaving AIT development
  to individual developers: most installers (e.g., Amazon AppStore, DTIgnite, Baidu)
  are riddled with various security-critical loopholes, which can be exploited by
  attackers to silently install any apps, acquiring dangerous-level permissions or
  even unauthorized access to system resources. Surprisingly, vulnerabilities were
  found in all steps of AIT. The attacks we present, dubbed Ghost Installer Attack
  (GIA), are found to pose a realistic threat to Android ecosystem. Further, we developed
  both a user-app-level and a system-level defense that are innovative and practical.'
publication: '*47th Annual IEEE/IFIP International Conference on Dependable Systems
  and Networks (DSN ''17)*'
doi: 10.1109/DSN.2017.33
---
