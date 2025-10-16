---
layout: default
title: Page 1
---

Guilds

<ul>
    {% for g in site.data.guilds.guilds %}
    <p class="notice-text" face="arial" size="1">{{ g }}</p>
    {% endfor %}
</ul>