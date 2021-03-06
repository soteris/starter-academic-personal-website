---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Draco: A System for Uniform and Fine-grained Access Control for Web Code on
  Android'
subtitle: ''
summary: ''
authors:
- Guliz Seray Tuncay
- Soteris Demetriou
- Carl A. Gunter
tags:
- '"access control"'
- '"android"'
- '"exploitation"'
- '"HTML5"'
- '"javascript"'
- '"javascript bridges"'
- '"origin"'
- '"webview"'
categories: []
date: '2016-10-01'
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
publishDate: '2021-03-06T19:19:42.174710Z'
publication_types:
- '1'
abstract: In-app embedded browsers are commonly used by app developers to display
  web content without having to redirect the user to heavy-weight web browsers. Just
  like the conventional web browsers, embedded browsers can allow the execution of
  web code. In addition, they provide mechanisms (viz., JavaScript bridges) to give
  web code access to internal app code that might implement critical functionalities
  and expose device resources. This is intrinsically dangerous since there is currently
  no means for app developers to perform origin-based access control on the JavaScript
  bridges, and any web code running in an embedded browser is free to use all the
  exposed app and device resources. Previous work that addresses this problem provided
  access control solutions that work only for apps that are built using hybrid frameworks.
  Additionally, these solutions focused on protecting only the parts of JavaScript
  bridges that expose permissions-protected resources. In this work, our goal is to
  provide a generic solution that works for all apps that utilize embedded web browsers
  and protects all channels that give access to internal app and device resources.
  Towards realizing this goal, we built Draco, a uniform and fine-grained access control
  framework for web code running on Android embedded browsers (viz., WebView). Draco
  provides a declarative policy language that allows developers to define policies
  to specify the desired access characteristics of web origins in a fine-grained fashion,
  and a runtime system that dynamically enforces the policies. In contrast with previous
  work, we do not assume any modifications to the Android operating system, and implement
  Draco in the Chromium Android System WebView app to enable seamless deployment.
  Our evaluation of the the Draco runtime system shows that Draco incurs negligible
  overhead, which is in the order of microseconds.
publication: '*Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications
  Security*'
url_pdf: https://doi.org/10.1145/2976749.2978322
doi: 10.1145/2976749.2978322
---
