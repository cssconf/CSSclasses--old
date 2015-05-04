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
      {% include team_item.html name=member.name twitter=member.twitter github=member.github %}
    {% endfor %}
  </ul>
{% endif %}

{% if site.data.coaches %}
## Coaches

  <ul class="team">
    {% for coach in site.data.coaches %}
      {% include team_item.html name=coach.name twitter=coach.twitter github=coach.github %}
    {% endfor %}
  </ul>
{% endif %}

{% if site.data.alumni2014 %}
## Alumni 2014

  <ul class="team">
    {% for alumni in site.data.alumni2014 %}
      {% include team_item.html name=alumni.name twitter=alumni.twitter github=alumni.github %}
    {% endfor %}
  </ul>
{% endif %}
