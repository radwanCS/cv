---
layout: archive
title: "Selected Projects"
permalink: /projects/
author_profile: true
toc: true
---

{% include base_path %}
{% assign sortedProjects = site.projects | sort: 'date' | reverse %}

This page contains a selection of my current and previous research/course/toy projects, categorized by topic. --- _Last updated in October 2024_.

## Artificial intelligence
---

{% for post in sortedProjects %}
  {% if post.topic == 'artificial_intelligence' %}
    {% include archive-single-project.html %}
  {% endif %}
{% endfor %}

## Software Development
---

{% for post in sortedProjects %}
  {% if post.topic == 'software_development' %}
    {% include archive-single-project.html %}
  {% endif %}
{% endfor %}

<!--
## Web Development
---

{% for post in sortedProjects %}
  {% if post.topic == 'web_development' %}
    {% include archive-single-project.html %}
  {% endif %}
{% endfor %}

## Others
---

{% for post in sortedProjects %}
  {% if post.topic == 'others' %}
    {% include archive-single-project.html %}
  {% endif %}
{% endfor %}
-->
