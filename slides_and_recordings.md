---
layout: page
title: Slides & Recordings 
image: '/assets/aws_il_user_group_big.jpeg'
permalink: /slides_and_recordings/
---
## Slides & Recordings
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

