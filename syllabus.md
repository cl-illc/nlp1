---
layout: photolist
title: Syllabus
menu: yes
---

*NLP1 2018*


# Lectures

{% assign lectures = (site.data.2018.lectures | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


