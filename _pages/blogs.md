---
layout: single
permalink: /blogs/
author_profile: true
title:  "Blogs"
header: 
 image: assets/images/aoh_banner.png
date:   2021-01-30 11:36:18 +0000
categories: jekyll update
---
{% for post in site.posts %}
## [{{post.title}}]({{site.baseurl}}{{post.url}})
<img src="../{{post.main_picture}}" />
{% endfor %}