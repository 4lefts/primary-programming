---
title: Year 3
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

{%- if collections.y3 %}

<ol>
{%- for project in collections.y3 -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{%- endfor -%}
</ol>
{%- else %}
Projects coming soon
{%- endif -%}
