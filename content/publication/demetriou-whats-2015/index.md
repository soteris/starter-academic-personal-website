---
# Documentation: https://wowchemy.com/docs/managing-content/

title: What's in Your Dongle and Bank Account? Mandatory and Discretionary Protection
  of Android External Resources
subtitle: ''
summary: ''
authors:
- Soteris Demetriou
- Xiaoyong Zhou
- Muhammad Naveed
- Yeonjoon Lee
- Kan Yuan
- XiaoFeng Wang
- Carl A Gunter
tags: []
categories: []
date: '2015-01-01'
lastmod: 2021-03-06T18:52:33Z
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
publishDate: '2021-03-06T18:52:33.381148Z'
publication_types:
- '1'
abstract: 'The pervasiveness of security-critical external resources (e.g accessories,
  online services) poses new challenges to Android security. In prior research we
  revealed that given the BLUETOOTH and BLUETOOTH_ADMIN permissions, a malicious app
  on an authorized phone gains unfettered access to any Bluetooth device (e.g., Blood
  Glucose meter, etc.). Here we further show that sensitive text messages from online
  banking services and social networks (account balance, password reset links, etc.)
  are completely exposed to any app with either the RECEIVE_SMS or the READ_SMS permission.
  Similar security risks are present in other channels (Internet, Audio and NFC) extensively
  used to connect the phone to assorted external devices or services. Fundamentally,
  the current permission-based Discretionary Access Control (DAC) and SEAndroid-based
  Mandatory Access Control (MAC) are too coarse-grained to protect those resources:
  whoever gets the permission to use a channel is automatically allowed to access
  all resources attached to it.'
publication: '*Proceedings 2015 Network and Distributed System Security Symposium*'
url_pdf: https://www.ndss-symposium.org/ndss2015/ndss-2015-programme/whats-your-dongle-and-bank-account-mandatory-and-discretionary-protection-android-external/
doi: 10.14722/ndss.2015.23098
---
