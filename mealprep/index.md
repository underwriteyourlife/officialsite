---
 layout: archive
 permalink: /mealprep/
 title: "Meal Prep"
 author_profile: false
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category="Meal Prep" %}
    Cats
	  <!--{% include post-grid.html %}-->
  {% endif %}
{% endfor %}
</div><!-- /.tiles -->

<!--
{% include base_path %}
{% include group-by-array collection=site.posts field="Meal Prep" %}

{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
-->
