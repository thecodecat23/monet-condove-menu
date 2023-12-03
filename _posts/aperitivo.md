---
layout: page
title: Aperitivo
permalink: /aperitivo/
---

# Aperitivo al Caffè Monet

L'aperitivo al Caffè Monet è il modo perfetto per rilassarsi prima del pranzo o della cena.

## Menu Aperitivo

{% for item in site.data.aperitivo %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}