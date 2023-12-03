---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Benvenuti al Caffè Monet, Condove
---

## Menu

- [Colazione](/colazione/)
- [Pranzo](/pranzo/)
- [Aperitivo](/aperitivo/)
- [Birre](/birre/)

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