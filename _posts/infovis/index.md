---
 layout: archive
 title:  "信息可视化笔记"
 categories: posts\infovis
image:
   teaser: xxkshN1.png
   feature: xxkshN1.png
---

<div class="tiles">
{% for post in site.categories.posts\infovis %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts\infovis 的列出来---->