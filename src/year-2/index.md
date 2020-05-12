---
title: Year 2
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

{%- if collections.y2 %}

<ol>
{%- for project in collections.y2 -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{%- endfor -%}
</ol>
{%- else %}
Projects coming soon
{%- endif -%}
