---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Resolving the Predicament of Android Custom Permissions
subtitle: ''
summary: ''
authors:
- Güliz Seray Tuncay
- Soteris Demetriou
- Karan Ganju
- Carl A. Gunter
tags: []
categories: []
date: '2018-01-01'
lastmod: 2021-03-06T18:52:32Z
featured: true
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
projects: ["authentication-authorization-and-access-control"]
publishDate: '2021-03-06T19:32:02.456116Z'
publication_types:
- '1'
abstract: Android leverages a set of system permissions to protect platform resources.
  At the same time, it allows untrusted third-party applications to declare their
  own custom permissions to regulate access to app components. However, Android treats
  custom permissions the same way as system permissions even though they are declared
  by entities of different trust levels. In this work, we describe two new classes
  of vulnerabilities that arise from the ‘predicament’ created by mixing system and
  custom permissions in Android. These have been acknowledged as serious security
  ﬂaws by Google and we demonstrate how they can be exploited in practice to gain
  unauthorized access to platform resources and to compromise popular Android apps.
  To address the shortcomings of the system, we propose a new modular design called
  Cusper for the Android permission model. Cusper separates the management of system
  and custom permissions and introduces a backward-compatible naming convention for
  custom permissions to prevent custom permission spooﬁng. We validate the correctness
  of Cusper by 1) introducing the ﬁrst formal model of Android runtime permissions,
  2) extending it to describe Cusper, and 3) formally showing that key security properties
  that can be violated in the current permission model are always satisﬁed in Cusper.
  To demonstrate Cusper’s practicality, we implemented it in the Android platform
  and showed that it is both effective and efﬁcient.
publication: '*Proceedings 2018 Network and Distributed System Security Symposium (NDSS ''18)*. *Acceptance rate=21.4% (71/331)*'
url_pdf: https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_08-4_Tuncay_paper.pdf
doi: 10.14722/ndss.2018.23210
links:
  - name: Slides
    url: 'ndss2018_release_slides.pdf'
  - name: Presentation Video
    url: 'https://www.youtube.com/watch?v=9TFAYgUcsk8'
  - name: Source Code (Formal Model)
    url: 'https://github.com/gulizseray/alloy-android-permissions'
  - name: 'Website'
    url: 'https://sites.google.com/view/cusper-custom-permissions/home'
---
### :trophy: Awards
> Distinguished Paper Award at NDSS '18

> Finalist at the Cybersecurity Awareness Worldwide (CSAW) applied research competition
