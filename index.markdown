---
layout: home
---

# Benvenuti al Caffè Monet, Condove
---

### Colazione
{% for item in site.data.colazione %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Pranzo
{% for item in site.data.pranzo %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Aperitivo
{% for item in site.data.aperitivo %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}

### Birre
{% for item in site.data.birre %}
- **{{ item.name }}**: {{ item.description }} - €{{ item.price }}
{% endfor %}