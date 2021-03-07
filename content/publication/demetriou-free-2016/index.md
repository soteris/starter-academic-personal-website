---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Free for All! Assessing User Data Exposure to Advertising Libraries on Android
subtitle: ''
summary: ''
authors:
- Soteris Demetriou
- Whitney Merrill
- Wei Yang
- Aston Zhang
- Carl A. Gunter
tags: []
categories: []
date: '2016-01-01'
lastmod: 2021-03-06T18:52:33Z
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
projects: []
publishDate: '2021-03-06T19:32:03.278142Z'
publication_types:
- '1'
abstract: 'Many studies focused on detecting and measuring the security and privacy
  risks associated with the integration of advertising libraries in mobile apps. These
  studies consistently demonstrate the abuses of existing ad libraries. However, to
  fully assess the risks of an app that uses an advertising library, we need to take
  into account not only the current behaviors but all of the allowed behaviors that
  could result in the compromise of user data conﬁdentiality. Ad libraries on Android
  have potential for greater data collection through at least four major channels:
  using unprotected APIs to learn other apps’ information on the phone (e.g., app
  names); using protected APIs via permissions inherited from the host app to access
  sensitive information (e.g. Google and Facebook account information, geo locations);
  gaining access to ﬁles which the host app stores in its own protection domain; and
  observing user inputs into the host app.'
publication: '*Proceedings of the 23rd Network and Distributed System Security Symposium (NDSS '16)*. *Acceptance rate=15.4%(60/389);*'
url_pdf: https://www.ndss-symposium.org/wp-content/uploads/2017/09/free-for-all-assessing-user-data-exposure-advertising-libraries-android.pdf
doi: 10.14722/ndss.2016.23082
links:
  - name: 'Slides'
    url: 'https://www.soterisdemetriou.com/publication/demetriou-free-2016/ndss2016-slides.pdf'
  - name: 'Source Code'
    url: 'https://github.com/soteris/android-advertising-pluto'
  - name: 'Project Website'
    url: 'https://sites.google.com/site/advertisingpluto/home'
---
