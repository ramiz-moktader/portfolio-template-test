---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

  <ul> {% include base_path %}
    {% for post in site.projects %}
      {% include archive-single-talk.html %}
    {% endfor %}
    </ul>