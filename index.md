---
layout: page
image: '/assets/aws_il_user_group_big.jpeg'
---
## Welcome to AWS Israel Community web site

### Coming meetups
<ul>
{% for meetup in site.data.coming_meetups %}
  <li>
    <a href="{{ meetup.link }}">
      {{ meetup.name }} - {{ meetup.local_date }} {{ meetup.local_time }} @ {{ meetup.venue.name }}
    </a>
  </li>
{% endfor %}
</ul>

### Past meetups

#### 2018
<ul>
{% for meetup in site.data.past_meetups_2018 %}
  <li>
    <a href="{{ meetup.link }}">
      {{ meetup.name }}
    </a>
  </li>
{% endfor %}
</ul>

#### 2017
<ul>
{% for meetup in site.data.past_meetups_2017 %}
  <li>
    <a href="{{ meetup.link }}">
      {{ meetup.name }}
    </a>
  </li>
{% endfor %}
</ul>

#### 2016
<ul>
{% for meetup in site.data.past_meetups_2016 %}
  <li>
    <a href="{{ meetup.link }}">
      {{ meetup.name }}
    </a>
  </li>
{% endfor %}
</ul>

#### 2015
<ul>
{% for meetup in site.data.past_meetups_2015 %}
  <li>
    <a href="{{ meetup.link }}">
      {{ meetup.name }}
    </a>
  </li>
{% endfor %}
</ul>
