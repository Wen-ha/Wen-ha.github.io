---
 layout: archive
 title:  "信息可视化笔记"
 categories: postsinfovis
image:
   feature: xxkshN1.png
---

<div class="tiles">
{% for post in site.categories.postsinfovis %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 postsinfovis 的列出来---->