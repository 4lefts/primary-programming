---
title: Year 6
tags: years
---

# {{title}}

## Objectives

{% for curriculum in collections.curricula -%}
{%- if curriculum.data.title == title -%}
{{curriculum.templateContent}}
{%- endif -%}
{%- endfor %}

## Projects

{%- if collections.y6 %}

<ol>
{%- for project in collections.y6 -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{%- endfor -%}
</ol>
{%- else %}
Projects coming soon
{%- endif -%}
