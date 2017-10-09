---
 layout: archive
 permalink: /mealprep/
 title: "Meal Prep"
 author_profile: false
---

{% for post in site.categories.mealprep %}
    # render the photo post html
{% endfor %}

<!--
{% include base_path %}
{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
-->
