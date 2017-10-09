---
 layout: archive
 permalink: /recipes/
 title: "Recipes"
 author_profile: false
---

{% for post in site.posts %}
  {% if post.category == "Recipe"%}
    {% include post-grid.html %}
  {% endif %}
{% endfor %}
