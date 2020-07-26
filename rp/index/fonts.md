# Packs containing fonts
---
{% include packs/footer.md %}

---
{% for item in site.data.fonts.packs %}
    [{{ item.title }}]({{ item.url }})
{% endfor %}