---
layout: archive
author_profile: false
---

Examples under development. Nothing to see...

{% include base_path %}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent examples" }}</h3>

{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include paginator.html %}