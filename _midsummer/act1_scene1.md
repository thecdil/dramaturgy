---
title: Act 1, Scene 1
act: 1
scene: 1
actscene: 1.1
---

{%- assign lines = site.data.midsummer -%}
{% for line in lines %}
{% if line.ActScene contains page.actscene %}
{{ line.ActSceneLine}} {{ line.Player }}: {{ line.PlayerLine }}
{% endif %}
{% endfor %}
