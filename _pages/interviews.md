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

<iframe src="https://embed.acast.com/607d581b77978d4bc09c32d6?cover=true&episode-order=asc&feed=true" frameBorder="0" allow="autoplay" width="100%" height="375"></iframe>

{% for post in site.interviews %}
## {{post.title}}
{{post.description}}
<div class="responsive-video-container">
    <iframe src="{{post.embed}}" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowfullscreen></iframe>
  </div>
{% endfor %}



