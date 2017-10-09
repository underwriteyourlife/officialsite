---
 layout: archive
 permalink: /mealprep/
 title: "Meal Prep"
 author_profile: false
---

{% include base_path %}
{% include group-by-array collection=site.posts field="categories" %}

{% for post in site.posts %}
  {% if post.category == "Meal Prep"%}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
