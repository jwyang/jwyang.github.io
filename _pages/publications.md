---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my full article list on <a href="https://scholar.google.com/citations?user=Cl9byD8AAAAJ&hl=en">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
