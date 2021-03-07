---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'HanGuard: SDN-driven protection of smart home WiFi devices from malicious
  mobile apps'
subtitle: ''
summary: ''
authors:
- Soteris Demetriou
- Nan Zhang
- Yeonjoon Lee
- XiaoFeng Wang
- Carl A. Gunter
- Xiaoyong Zhou
- Michael Grace
tags:
- '"Android"'
- '"iOS"'
- '"IoT"'
- '"security"'
- '"wireless networks"'
categories: []
date: '2017-07-01'
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
projects: []
publishDate: '2021-03-06T19:32:03.004072Z'
publication_types:
- '1'
abstract: 'A new development of smart-home systems is to use mobile apps to control
  IoT devices across a Home Area Network (HAN). As verified in our study, those systems
  tend to rely on the Wi-Fi router to authenticate other devices. This treatment exposes
  them to the attack from malicious apps, particularly those running on authorized
  phones, which the router does not have information to control. Mitigating this threat
  cannot solely rely on IoT manufacturers, which may need to change the hardware on
  the devices to support encryption, increasing the cost of the device, or software
  developers who we need to trust to implement security correctly. In this work, we
  present a new technique to control the communication between the IoT devices and
  their apps in a unified, backward-compatible way. Our approach, called HanGuard,
  does not require any changes to the IoT devices themselves, the IoT apps or the
  OS of the participating phones. HanGuard uses an SDN-like approach to offer fine-grained
  protection: each phone runs a non-system userspace Monitor app to identify the party
  that attempts to access the protected IoT device and inform the router through a
  control plane of its access decision; the router enforces the decision on the data
  plane after verifying whether the phone should be allowed to talk to the device.
  We implemented our design over both Android and iOS (textgreater 95% of mobile OS
  market share) and a popular router. Our study shows that HanGuard is both efficient
  and effective in practice.'
publication: '*Proceedings of the 10th ACM Conference on Security and Privacy in Wireless
  and Mobile Networks (ACM WiSec ''17)*. *Acceptance rate=32.9% (28/85)*'
url_pdf: https://doi.org/10.1145/3098243.3098251
doi: 10.1145/3098243.3098251
links:
  - name: 'Slides'
    url: 'https://www.soterisdemetriou.com/publication/demetriou-hanguard-2017/HanGuard_WiSec_Presentation_public.pdf'
  - name: 'Demo Video'
    url: 'https://www.youtube.com/watch?v=AuRP3IUdeuc'
  - name: 'Project Website'
    url: 'https://sites.google.com/site/projecthanguard/home'
---
