---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my papers on <a href="https://scholar.google.com/citations?user=IcrIWXAAAAAJ">my Google Scholar profile</a>.


{% include base_path %}
<ol>
{% for post in site.publications reversed %}
<li>
  {% include archive-single.html %}
  <hr>
</li>
{% endfor %}
</ol>
