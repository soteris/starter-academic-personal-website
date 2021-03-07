---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DarkneTZ: towards model privacy at the edge using trusted execution environments'
subtitle: ''
summary: ''
authors:
- Fan Mo
- Ali Shahin Shamsabadi
- Kleomenis Katevas
- Soteris Demetriou
- Ilias Leontiadis
- Andrea Cavallaro
- Hamed Haddadi
tags: []
categories: []
date: '2020-06-01'
lastmod: 2021-03-06T18:52:31Z
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
projects:
  - security-in-machine-learning-and-cps
  - mobile-devices-and-iot-systems-security
publishDate: '2021-03-06T19:32:01.767990Z'
publication_types:
- '1'
abstract: We present DarkneTZ, a framework that uses an edge device's Trusted Execution
  Environment (TEE) in conjunction with model partitioning to limit the attack surface
  against Deep Neural Networks (DNNs). Increasingly, edge devices (smartphones and
  consumer IoT devices) are equipped with pre-trained DNNs for a variety of applications.
  This trend comes with privacy risks as models can leak information about their training
  data through effective membership inference attacks (MIAs). We evaluate the performance
  of DarkneTZ, including CPU execution time, memory usage, and accurate power consumption,
  using two small and six large image classification models. Due to the limited memory
  of the edge device's TEE, we partition model layers into more sensitive layers (to
  be executed inside the device TEE), and a set of layers to be executed in the untrusted
  part of the operating system. Our results show that even if a single layer is hidden,
  we can provide reliable model privacy and defend against state of the art MIAs,
  with only 3% performance overhead. When fully utilizing the TEE, DarkneTZ provides
  model protections with up to 10% overhead.
publication: '*Proceedings of the 18th International Conference on Mobile Systems,
  Applications, and Services (MobiSys ''20)*. *Acceptance rate=19.4% (34/175)*'
url_pdf: https://doi.org/10.1145/3386901.3388946
doi: 10.1145/3386901.3388946
links:
  - name: Presentation Video
    url: 'https://www.youtube.com/watch?v=mEAlONq3MU4'
  - name: Source Code
    url: 'https://github.com/mofanv/darknetz'
---
