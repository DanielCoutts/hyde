---
layout: page
title: Projects
---

{% for node in site.data.menu %}
  {% if node.title == "Projects" %}
    {% for project in node.projects %}

{% include project_summary.html project=project %}
{% include project_images.html images=project.images %}
{% include project_links.html links=project.links %}

    {% endfor %}
  {% endif %}
{% endfor %}
