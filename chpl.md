---
title: うさぎさんでもわかる並列言語Chapel
subtitle: Chapel the Parallel Programming Language
topics: Chapel,並列処理,高性能計算,PGAS,HPC
pdf: chpl.pdf
web: https://zenn.dev/nextzlog/books/chapel-the-parallel-programming-language
---
{% for file in site.static_files %}
{% if file.basename contains 'chpl.' and file.extname == '.svg' %}
<img src="{{file.path}}" class="img-thumbnail img-fluid" width="100%">
{% endif %}
{% endfor %}
