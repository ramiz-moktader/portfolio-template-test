---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
redirect_from:
  - /project
---

  <ul> {% include base_path %}
    {% for post in site.projects %}
      {% include archive-single.html %}
    {% endfor %}
    </ul>