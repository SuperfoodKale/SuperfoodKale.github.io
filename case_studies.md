---
layout: splash
author_profile: false
title: Case Studies
---
A collection of issues I've diagnosed and resolved across hardware, software, and systems.

{% assign studies = site.case_studies | sort: "order" %}
{% for study in studies %}

---

### [{{ study.title }}]({{ study.url }})

**Category:** {{ study.category }}

{{ study.excerpt }}

{% endfor %}
