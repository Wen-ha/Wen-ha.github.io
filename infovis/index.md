---
layout: default
title:  "信息可视化作品集"
categories: infovis
---

<div class="tiles">
{% for post in site.categories.infovis %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来---->