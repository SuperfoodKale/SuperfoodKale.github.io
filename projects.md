
---
layout: splash
author_profile: false
title: Projects
---
A collection of Projects I have completed

{% assign projects = site.projects | sort: "order" %}
{% for project in projects %}

---

### [{{ project.title }}]({{ project.url }})

**Category:** {{ project.category }}

{{ project.excerpt }}

{% endfor %}
