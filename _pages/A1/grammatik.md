---
title: A1- Grammatik
type: page
permalink: /A1/grammatik
---

## A1- Grammatik
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a1_grammatik' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>