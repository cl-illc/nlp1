---
layout: photolist
title: Practicals
menu: true
---
*Autumn 2018*

Guidelines for [assessment](assessment)

# Practicals


{% assign practicals = (site.data.2018.assignments | where: "selected", "y") %}
{% for practical in practicals %}
{% include assignment.html lecture=practical %}
{% endfor %}

