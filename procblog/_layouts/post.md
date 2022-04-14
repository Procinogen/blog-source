---
layout: default
---

<h1>{{ page.title }}</h1>
{%- assign date_format = "%Y-%m-%d" -%}
<h4 class="post-date">{{ page.date | date: date_format }}</h4>

<hr/>

{{ content }}