---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: default
title: "Learning how to build websites with Jekyll"
---

Starting to create a webpage

## Description
{{ site.description }}

{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](about#team).


[Predefined config variables](https://jekyllrb.com/docs/variables#site-variables)
 
See some [examples of our work]({{ page.lesson-example }})

