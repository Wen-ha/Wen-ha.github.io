---
 layout: archive
 title:  "信息可视化作品集"
 categories: infovis
---

<a href="https://public.tableau.com/shared/NDR4SFPRR?:display_count=yes" target="_blank">![数据分析.png](https://i.loli.net/2018/01/07/5a51dae1bd0a2.png)</a>

<div class="tiles">
{% for post in site.categories.infovis %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来---->