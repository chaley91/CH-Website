---
layout: default
title: About
---
# About

This is my little corner of the Internet.  Welcome!

Social media:

<ul>
{% for socialmedia in site.data.socialmedia %}
  <li>
    <a href="{{ socialmedia.url }}">
      {{ socialmedia.name }}
    </a>
  </li>
{% endfor %}
</ul>

Websites I frequent:

<ul>
{% for link in site.data.links %}
  <li>
    <a href="{{ link.url }}">
      {{ link.name }}
    </a>
  </li>
{% endfor %}
</ul>
