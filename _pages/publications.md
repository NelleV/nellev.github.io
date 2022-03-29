---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=8QspsP0AAAAJ&hl=en">my Google Scholar profile</a>.


{% include base_path %}

<div class="publications">
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

</div>
