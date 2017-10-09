---
 layout: archive
 permalink: /recipes/
 title: "Recipes"
 author_profile: false
---

{% include base_path %}
{% include group-by-array collection=site.posts field="categories" %}

{% for post in site.posts %}
  {% if post.category == "Recipes"%}
    {% include post-grid.html %}
  {% endif %}
{% endfor %}
