---
title: Contributors
layout: about
permalink: /contributors.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

# Project Contributors
{:.pb-4}

{%- assign people = site.data.people -%}
{% for p in people %}

<div class="row py-3 contributors">
    <div class="col-md-3 pt-2 text-center">
        {%- assign photo = p.image | prepend: '/images/team/' -%}
        {% capture caption %}{{ p.name }}{% endcapture %}
        {% include feature/image.html src=photo caption=p.name %}
    </div>
    <div class="col-md-9">
        {{ p.description | markdownify }}
    </div>
</div>
    
{% endfor %}