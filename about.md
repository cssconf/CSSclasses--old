---
layout: page
title: About
permalink: /about/
---

CSSclasses is for beginners and experts alike: Using CSS as a simple and low-barrier entry language, we empower people to understand their browser and to learn how to experiment with code. Workshop and hackathon in one event.

## Team

CSSclasses is organized by the volunteer teams of CSSconf EU and OpenTechSchool.

{% if site.data.team %}
  <ul class="team">
    {% for member in site.data.team %}
      <li>{{ member.name }}: <a href="https://twitter.com/{{ member.twitter }}">@{{ member.twitter }}</a> <a href="https://github.com/{{ member.github }}">@{{ member.github }}</a></li>
    {% endfor %}
  </ul>
{% endif %}


## Coaches

{% if site.data.coaches %}
  <ul class="team">
    {% for coach in site.data.coaches %}
      <li>{{ coach.name }}: <a href="https://twitter.com/{{ coach.twitter }}">@{{ coach.twitter }}</a> <a href="https://github.com/{{ coach.github }}">@{{ coach.github }}</a></li>
    {% endfor %}
  </ul>
{% endif %}


## Alumni 2014

{% if site.data.alumni2014 %}
  <ul class="team">
    {% for alumni in site.data.alumni2014 %}
      <li>{{ alumni.name }}: <a href="https://twitter.com/{{ alumni.twitter }}">@{{ alumni.twitter }}</a> <a href="https://github.com/{{ alumni.github }}">@{{ alumni.github }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
