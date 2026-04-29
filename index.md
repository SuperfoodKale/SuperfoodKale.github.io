---
layout: splash
author_profile: false
---

A collection of projects and case studies from things I've built and worked through.

---

## Case Studies

{% assign studies = site.case_studies | sort: "order" | limit: 3 %}
{% for study in studies %}

### [{{ study.title }}]({{ study.url }})

**Category:** {{ study.category }}

{{ study.excerpt }}

---
{% endfor %}

[View all case studies →](case_studies.md)

---

## Projects

{% assign projects = site.projects | sort: "order" | limit: 3 %}
{% for project in projects %}

### [{{ project.title }}]({{ project.url }})

**Category:** {{ project.category }}

{{ project.excerpt }}

---
{% endfor %}

[View all projects →](projects.md)