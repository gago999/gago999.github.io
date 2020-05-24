---
layout: name
title: Home

section: Home
---

<img class='inset right' src='/images/mark_reid.jpg' title='Mark Reid' alt='Photo of Mark Reid drinking a coffee' width='120px' />

你好！
=======

陈奕涵，JLUZH金融学专业，曾先后获得全国大学生数学建模竞赛广东赛区二等奖、美国大学生数学建模竞赛国际二等奖。现阶段学习方向：数据处理、商业分析。

+--	{.section}
博客
========

目前我主要更新的是放在阿里云服务器上的<a href="https://gago9.cn/" target="_blank">Typecho博客</a>，主要记录学习过程的心得体会。
Recent posts include:
{% for post in site.categories.iem limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}

