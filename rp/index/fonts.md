# Packs containing fonts
---
{% include packs/footer.md %}

---
{% for item in site.data.fonts.packs %}
<a href="{{ site.baseurl }}/rp/{{ item.url }}.html">{{ item.title }}</a>
{% endfor %}
