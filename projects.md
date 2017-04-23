---
layout: page
title: Projects
---

{% for node in site.data.menu %}
  {% if node.title == "Projects" %}
    {% for project in node.projects %}

{% include project_summary.html project=project %}

    {% endfor %}
  {% endif %}
{% endfor %}
