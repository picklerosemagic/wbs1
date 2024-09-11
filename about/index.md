---
layout: page
title: About
title_fr: About_fr
current: about
cover: 'assets/images/about.jpg'
show_boxes: true
---

{% if site.data.l10n.lang contains 'en' %}
	{% include_relative en/about.md %}
{% else %}
	{% include_relative fr/about.md %}
{% endif %} 