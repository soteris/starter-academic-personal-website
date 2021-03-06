---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Identity, location, disease and more: inferring your secrets from android
  public resources'
subtitle: ''
summary: ''
authors:
- Xiaoyong Zhou
- Soteris Demetriou
- Dongjing He
- Muhammad Naveed
- Xiaorui Pan
- XiaoFeng Wang
- Carl A. Gunter
- Klara Nahrstedt
tags:
- '"information leaks"'
- '"mobile security"'
- '"privacy"'
categories: []
date: '2013-11-01'
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
publishDate: '2021-03-06T19:24:20.775917Z'
publication_types:
- '1'
abstract: "The design of Android is based on a set of unprotected shared resources,\
  \ including those inherited from Linux (e.g., Linux public directories). However,\
  \ the dramatic development in Android applications (app for short) makes available\
  \ a large amount of public background information (e.g., social networks, public\
  \ online services), which can potentially turn such originally harmless resource\
  \ sharing into serious privacy breaches. In this paper, we report our work on this\
  \ important yet understudied problem. We discovered three unexpected channels of\
  \ information leaks on Android: per-app data-usage statistics, ARP information,\
  \ and speaker status (on or off). By monitoring these channels, an app without any\
  \ permission may acquire sensitive information such as smartphone user's identity,\
  \ the disease condition she is interested in, her geo-locations and her driving\
  \ route, from top-of-the-line Android apps. Furthermore, we show that using existing\
  \ and new techniques, this zero-permission app can both determine when its target\
  \ (a particular application) is running and send out collected data stealthily to\
  \ a remote adversary. These findings call into question the soundness of the design\
  \ assumptions on shared resources, and demand effective solutions. To this end,\
  \ we present a mitigation mechanism for achieving a delicate balance between utility\
  \ and privacy of such resources."
publication: '*Proceedings of the 2013 ACM SIGSAC conference on Computer & communications
  security*'
url_pdf: https://doi.org/10.1145/2508859.2516661
doi: 10.1145/2508859.2516661
---
