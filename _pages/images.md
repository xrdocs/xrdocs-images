---
layout: default
permalink: /images_what
---

{% include base_path %}

{% for image in site.static_files %}
        <p>{{image.path}}</p>
{% endfor %}
