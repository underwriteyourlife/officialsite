---
 layout: archive
 permalink: /recipesforfailure/
 title: "Recipes for Failure"
 author_profile: false
---

{% include base_path %}
{% include group-by-array collection=site.posts field="categories" %}

{% for post in site.posts %}
  {% if post.category == "Recipe Failure"%}
    {% include post-grid.html %}
  {% endif %}
{% endfor %}
