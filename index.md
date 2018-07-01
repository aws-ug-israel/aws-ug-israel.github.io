---
layout: page
image: '/assets/aws_il_user_group_big.jpeg'
---
## Welcome to AWS Israel Community web site

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
