---
layout: single
permalink: /interviews/
author_profile: true
title:  "Interviews"
header: 
 image: assets/images/aoh_banner.png
date:   2021-01-30 11:36:18 +0000
categories: jekyll update
---

{% for post in site.interviews %}
## {{post.title}}
{{post.description}}
<div class="responsive-video-container">
    <iframe src="{{post.embed}}" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowfullscreen></iframe>
  </div>
{% endfor %}

