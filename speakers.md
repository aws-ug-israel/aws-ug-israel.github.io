---
layout: page
title: Speakers
image: '/assets/aws_il_user_group_big.jpeg'
permalink: /speakers/
---
## Our speekers

<ul>
{% for speaker in site.data.speakers_list %}
  <li>
    <a href="{{ speaker.LinkedIn }}">
      {{ speaker.first_name }} {{ speaker.last_name }}
    </a>
  </li>
{% endfor %}
</ul>


