---
layout: default
title: Guildas
---

# Guildas

{% for g in site.data.guilds.guilds %}
---

## {{ g.name }}
<aside>Localização: Distrito X</aside>
{{ g.description }}
{% endfor %}
