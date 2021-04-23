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

## Interviews
You can watch the following interviews as videos or, alternatively, you can listen to them here on the Agent of History podcast.
<iframe src="https://embed.acast.com/607d581b77978d4bc09c32d6?cover=true&episode-order=asc&ga=false&feed=true" frameBorder="0" allow="autoplay" width="100%" height="375"></iframe>

{% for post in site.interviews %}
## {{post.title}}
{{post.description}}
<div class="responsive-video-container">
    <iframe src="{{post.embed}}" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowfullscreen></iframe>
  </div>
{% endfor %}

