---
layout: page
title: Projects
---

{% for node in site.data.menu %}
  {% if node.title == "Projects" %}
    {% for project in node.subitems %}

{% include project_summary.html title="Dyne" image_url="http://placehold.it/200x200" description="test" %}

    {% endfor %}
  {% endif %}
{% endfor %}

<!-- {% include posts_with_tag.html %} -->
