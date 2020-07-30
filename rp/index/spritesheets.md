# Packs containing sprite sheets
---
{% include packs/footer.md %}

---
{% for item in site.data.spritesheets.packs %}
<a href="{{ site.baseurl }}/rp/{{ item.url }}.html">{{ item.title }}</a>
{% endfor %}
