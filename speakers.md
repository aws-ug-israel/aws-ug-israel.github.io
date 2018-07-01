---
layout: page
title: Speakers
image: '/assets/aws_il_user_group_big.jpeg'
permalink: /speakers/
---
<script src="//platform.linkedin.com/in.js" type="text/javascript"></script>
## Our speekers
<ul>
{% for speaker in site.data.speakers_list %}
    <script type="IN/MemberProfile" data-id="{{ speaker.LinkedIn }}" data-format="inline" data-related="false"></script>
{% endfor %}
</ul>


